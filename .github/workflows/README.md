# Toolbelt Workflow

Goal: A mechanism that implements as many OpenSSF best practices using OpenSSF tools as possible in a way that is simple to use for project maintainers and easy for end users to check projects using this mechanism are following best practices and creating important security metadata (e.g. SBOMs, in-toto SLSA, etc.)

Secondary Goals:

- Highlight where there are gaps in OpenSSF and related practices, frameworks, and tools, or their adoption, especially in different ecosystems (e.g. Sigstore signatures are not supported in Maven)
- Highlight when implementing these practices or adopting the tools is difficult
Show examples following these practices and implementing the tools 

Outcomes:

- Maintainers should be able to use this mechanism to implement OpenSSF practices and adopt OpenSSF tooling, e.g. add SLSA to their build and turn on Scorecard.
- Maintainers should be able to easily know where data is generated, e.g. where SBOMs, SLSA, SAST reports, etc. live so they can use it for later analysis and understanding supply chain risks.
- End users should also be able to easily know where data is generated, e.g. where SBOMs, SLSA, SAST reports, etc. live so they can use it to make decisions on risk as well as analysis later on when vulnerabilities or supply chain incidents happen.

Requirements:

- Should be easy to update (e.g. dependency bot should not complain about a dozen things for you to update every other day)
- Should consist of pieces that easily interoperate.
- Should be as simple as possible for the user as possible

Proposed MVP Solution: A Github workflow-based solution for Go with Go being widely supported for most of the stuff we need
Implement as many of the scorecard, SLSA, and other OpenSSF best practices/requirements as possible.

---

## Toolbelt Workflow prototype

Tools included:

- Cosign (Signing)
- SLSA Github Generator (SLSA in-toto attestation generation)
- Goreleaser (Building Go artifact)
- Trivy (Building SBOM)

Outputs on release:

- SLSA attestations for every artifact in on DSSE document
- Individual SBOMs for every artifact generated following SBOM everywhere naming guide

Output storage:

- In OCI image for OCI images
- In the GitHub release for all other artifacts

Usage, in the user's GitHub workflow:

```yaml
name: toolbelt test
on:
  workflow_dispatch: # testing only, trigger manually to test it works
  push:
    branches: # Triggers snapshot
      - main
    tags: # Triggers full build (see toolbelt.yaml for how this works)
      - "v*"
permissions: read-all # This is for a scorecard check
jobs:
  toolbelt:
    permissions:
      contents: write # To upload assets to release.
      packages: write # To publish container images to GHCR
      id-token: write # Needed for signing the images with GitHub OIDC Token
      actions: read # Needed to read output of github actions
    uses: ossf/toolbelt/.github/workflows/toolbelt.yaml@toolbelt-workflow # This will change to a hash once merged in
```
