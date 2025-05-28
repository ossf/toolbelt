# Infrastructure/Platform Engineer Personas

## Name: Noor the Backend Infrastructure Engineer

### Role:
- Platform Reliability Engineer at a large e-commerce company

### Background:
- Noor keeps the lights on for everything behind the scenes—CI/CD, observability, and infra pipelines that support dev, data, and ML teams. If GitHub Actions break or a deployment stalls, he’s the one who gets the ping. He’s built a lot of Terraform and Argo stuff that’s now in use across his org, and he's always looking for cleaner, more secure ways to do things. He’s been lurking in OpenSSF repos but hasn’t yet made his first PR—just needs a nudge and some extra time between on-call rotations.

### Goals:
- Make infra boring—in a good way. Secure, predictable, and low-maintenance.
- Replace glue scripts with reusable modules others can depend on.

#### Personal
- Be the go-to person for building things that don’t break at 2AM
- Help others level up their automation game with built-in security

#### Project
- Contribute CI/CD security patterns others can drop into their pipelines
- Share some of his team's GitHub Actions back upstream

#### Company
- Keep build and deploy systems fast and secure
- Stay ahead of auditors and fire drills with solid infra hygiene

### Challenges:
- It’s hard to make time for upstream work when incidents eat the calendar
- Every team uses slightly different infra—unifying them is a puzzle
- IaC security best practices keep evolving—hard to keep pace
- Tools often assume ideal cloud-native setups that don’t reflect legacy realities

### How the OpenSSF can help:
- Publish hardened CI/CD templates others like Noor can adapt quickly
- Offer examples for GitHub Actions and Terraform that balance speed and safety
- Support async-first contributions and starter tasks for infra engineers on the go

---

## Name: Yasmine the Security Governance Lead

### Role:
- Security Policy Lead at an international research institute

### Background:
- Yasmine bridges the world of policy and engineering. She’s the one defining what “secure enough” means for dev environments, tools, and internal infra. She collaborates across compliance, security, and platform teams to keep things aligned and reduce risk without crushing velocity. Yasmine’s been watching OpenSSF’s policy and best practices work closely—and would love to contribute templates or reviews when she can.

### Goals:
- Make it easier for teams to do the right thing without friction
- Align internal policy with what the best OSS projects are already doing

#### Personal
- Champion security in a way that earns trust, not groans
- Create templates and playbooks that actually get used

#### Project
- Publish hardened environment baselines her org can reuse
- Get policy-as-code adopted beyond the security team

#### Organization
- Keep audits smooth and security posture strong
- Roll out consistent controls across globally distributed teams

### Challenges:
- Developers push back on policies they see as slowing them down
- Documentation for secure OSS tools is scattered or nonexistent
- Policy-as-code is powerful but not widely adopted yet
- Figuring out which OSS tools are safe to use takes a lot of legwork

### How the OpenSSF can help:
- Share reusable policy templates for securing dev environments and tooling
- Highlight projects that ship with sane, secure defaults
- Build bridges between governance pros across orgs to share real-world insights

---

## Name: Ravi the Cloud Platform Admin

### Role:
- DevOps/SRE Engineer running a multi-cloud ML platform

### Background:
- Ravi sets up and secures cloud infra for teams running data pipelines, training jobs, and production ML APIs. He’s got Terraform scripts, Helm charts, and just enough shell scripts to make it all work. Most of the time, he’s helping data scientists not accidentally expose credentials or exceed budget. He’s been using OpenSSF tools quietly to check dependencies and is thinking about upstreaming some hardened container images his team built.

### Goals:
- Make the platform secure by default—so users don’t have to think about it
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
- Cloud misconfigs are still the biggest fire hazard
- Many OSS ML tools don’t ship with basic security features
- Policy drift between dev/staging/prod is real and hard to detect
- Knowing which OSS projects are secure enough to use is still manual

### How the OpenSSF can help:
- Build Terraform/Helm integrations that catch security missteps early
- Offer pre-secured versions of popular ML OSS tools and containers
- Curate OSS components that meet basic security criteria and are actively maintained

- ---
//Baha for you!//
## Name: Ophelia the IT Infrastructure Engineer

### Role:
- Platform Reliability Engineer at a large e-commerce company

### Background:
- Noor keeps the lights on for everything behind the scenes—CI/CD, observability, and infra pipelines that support dev, data, and ML teams. If GitHub Actions break or a deployment stalls, he’s the one who gets the ping. He’s built a lot of Terraform and Argo stuff that’s now in use across his org, and he's always looking for cleaner, more secure ways to do things. He’s been lurking in OpenSSF repos but hasn’t yet made his first PR—just needs a nudge and some extra time between on-call rotations.

### Goals:
- Make infra boring—in a good way. Secure, predictable, and low-maintenance.
- Replace glue scripts with reusable modules others can depend on.

#### Personal
- Be the go-to person for building things that don’t break at 2AM
- Help others level up their automation game with built-in security

#### Project
- Contribute CI/CD security patterns others can drop into their pipelines
- Share some of his team's GitHub Actions back upstream

#### Company
- Keep build and deploy systems fast and secure
- Stay ahead of auditors and fire drills with solid infra hygiene

### Challenges:
- It’s hard to make time for upstream work when incidents eat the calendar
- Every team uses slightly different infra—unifying them is a puzzle
- IaC security best practices keep evolving—hard to keep pace
- Tools often assume ideal cloud-native setups that don’t reflect legacy realities

### How the OpenSSF can help:
- Publish hardened CI/CD templates others like Noor can adapt quickly
- Offer examples for GitHub Actions and Terraform that balance speed and safety
- Support async-first contributions and starter tasks for infra engineers on the go
