The following threats have been identified to be in scope that threaten the Secure Developer capability:

## TBT-1100 (Category) Actor merges malicious commit/regression/dependency
- Malicious Developer
- Untrained Developer
-- Lack of knowledge of security primitives affecting the code they produce
-- Incorrect or ineffective use of security technologies or tools
-- Lack of code documentation (or broken, incorrect, misleading)
-- Lack of awareness of privacy-by-design and security-by-design principles leads to data exposure
- Unverified/unauthenticated developer
-- Unchecked anonymous/community commit merged
## TBT-1200 (Category) Unauthorized Actor compromises legitimate account
- Compromised Developer Account (impersonation) 
- Developer under duress
- “Tail-gating”
## TBT-1300 (Category) Failure in tooling/configuration/process allows insertion of malicious software into codebase
- Security scanning tools not properly configured/ignored
- Project has no tooling./testing infra
- Compromised developer signing key
- No 2nd dev review commits prior to merge
- Lack of threat model for software introduces architectural or dependency weaknesses or vulnerabilities


## Assumptions
- Developer can be a project maintainer, contributor, or community member
- Developers have the ability to create new code, edit older code, integrate new 3rd party components or dependencies.  
- Only certain developers (maintainers) have the ability to push commits into main branch of software
- Initiation of a project may not start from a template or uses flawed template
- Not all projects include basic security capabilities/automated checks at initiation

