# Infrastructure/Platform Engineer Personas

## Name: Ravi the Cloud Platform Admin

### Role:
- DevOps/SRE Engineer running a multi-cloud ML platform

### Background:
- Ravi sets up and secures cloud infra for teams running data pipelines, training jobs, and production ML APIs. He’s got Terraform scripts, Helm charts, and just enough shell scripts to make it all work. Most of the time, he’s helping data scientists not accidentally expose credentials or exceed budget. He’s been using OpenSSF tools quietly to check dependencies and is thinking about upstreaming some hardened container images his team built.

### Goals:
- Make the platform secure so users don’t have to think about it
- Get better visibility into what OSS packages are being used and if they’re risky

#### Personal
- Learn from others solving similar cloud + ML + security problems
- Contribute tooling that helps teams ship safer infrastructure faster

#### Project
- Lock down model deployment with guardrails and automation
- Integrate supply chain checks into build and deploy workflows

#### Organization
- Meet internal and external compliance requirements without slowing teams down
- Standardize how OSS is tracked and patched across environments

### Challenges:
- Many OSS ML tools don’t ship with basic security features
- Policy drift between dev/staging/prod is real and hard to detect
- Knowing which OSS projects are secure enough to use is still a manual effort

### How the OpenSSF can help:
- Offer pre-secured versions of popular ML OSS tools and containers
- Curate OSS components that meet basic security criteria and are actively maintained

---
## Name: Ophelia the IT Infrastructure Engineer

### Role:
- Platform Reliability Engineer at a large e-commerce company

### Background:
- Ophelia keeps the lights on for everything behind the scenes in terms of tools, observability, and infrastructure that supports dev, data, and ML teams. If GitHub Actions break or a deployment stalls, she’s the one who gets the ping. She’s built a lot of Terraform and Argo workflows that are now used across her org, and she's always on the lookout for cleaner, more secure ways to do things. She’s been quietly exploring OpenSSF repos, and just needs a nudge (and some time between on-call shifts) to make her first upstream contribution.
  
### Goals:
- Make infra boring, in a good way. Secure, predictable, and low-maintenance.
- Replace glue scripts with reusable modules others can depend on.

#### Personal
- Provide development, data and ML teams with the tools, workflows and permissions they need to get the job done.
- Help others level up their automation game with built-in security

#### Project
- Contribute CI/CD security patterns others can drop into their pipelines

#### Company
- Keep build and deploy systems fast and secure
- Stay ahead of auditors and fire drills with solid infra hygiene

### Challenges:
- It’s hard to make time for upstream work when incidents eat the calendar
- IaC security best practices keep evolving—hard to keep pace

### How the OpenSSF can help:
- Offer examples for GitHub Actions and Terraform that balance speed and safety
