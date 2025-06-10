
# Security Engineer Personas

## Name: Finn the Finder

### Role: 
- Hacker
- Researcher
- Academic
- Bug/Bounty Hunter
- Concerned Software Enthusiast -- I find and/or research security vulnerabilities
- Consumer that discovers a vulnerability in implementation

### Background:
- Where there is software, there will be vulnerabilities. Finders intentionally, or unintentionally, discover vulnerabilities in software. Open source software has vulnerability disclosure processes that connect finders to projects/maintainers for developing a patch that downstream consumers of the open source can apply to remediate the vulnerability. Future versions of the open source should have the vulnerability closed, so downstream consumers of the software are not exposed to discovered vulnerabilities.  

#### Possible spectrum of experience:
- Job to do this
- In security and job is to notice
- Not a job, a hobby or accidental discovery

### Goals:
- Wants to discover vulnerabilities before threat actors.
- Wants recognition/credit for discovering complex and/or high severity vulnerabilities in order to grow their career

### Challenges:
- Unknowns caused by projects who do not have well published and public vulnerability disclosure policies
-Developers & vendors who are not responsive
-Vulnerabilities that I discover that get exploited in the wild

### How the OpenSSF can help:
- Continue to provide vulnerability disclosure process to connect finders to open source projects/maintainers
- Educate finder personas with the importance and availability of the open source security vulnerability disclosure process to encourage timely and secure reporting of vulnerabilities they find. 
- Software security development courses should have what to do if a vulnerability is disclosed. 
- Ethics of reporting a vulnerability vs sharing it as a zero day with threat actor
- Work to have this as part of Computer Science, Computer Information Systems academic programs: what to do if you find an open source project vulnerability (similar to how memory safe languages are taught in academic settings now to train future generations)
- Blogs. 
- Leverage DevRel and other industry events (speaking and booths) where the various roles learn (Blackhat/Defcon), Open Source Summits. 
- Lessons learned from not following the secure vulnerability disclosure process
- Address concerns when vulnerabilities are disclosed but not swiftly closed by open source projects/maintainers
- For high profile vulnerabilities, having a Security Incident Response Team (SIRT) in place to support projects where a Finder may have disclosed a high profile vulnerability that consumers are anxious to have closed but the priorities of the open source project may not be to close the identified security flaw.
- Incentivize open source projects/maintainers to close vulnerabilities. How can we offset the burden a disclosed vulnerability brings to an open source project/maintainer 
   Possibly Track  Mean Time to Remediate (MTTR) metrics tracked for “found” vulnerabilities and disclose the MTTR metric in security scorecard. There is nuance with CVEs, and effort can be expensive.
- Consumers of software can make automated decisions using the RISK metrics (built on security scorecard metrics) to understand open source projects that address “found” vulnerabilities in a timely manner (timely being a consumer's risk tolerance for using open source software with various MTTR).

---

## Name: Pang the Product Security Engineer

### Role:

* Security champion
* Product Security Engineer embedded in an engineering team
* Ensures good security controls are in place on the products (e.g. vulnerability remediation)

### Background:

Pang works at a large software enterprise where he sits directly with development teams to help "shift left" on security. Boyd has a lot of experience in secure SDLC, security standards, and controls. He doesn't write code that much, but, he’s very familiar with CI/CD pipelines, SAST/DAST tools, and dev tooling integrations. Boyd sees himself as the bridge between security policy and practical engineering constraints.

His role includes reviewing design documentation, running security assessments, and ensuring controls like authentication, access control, data protection, and vulnerability remediation are built into product roadmaps. He’s actively exploring how open source tools—especially from OpenSSF—can help embed security automation in his teams' pipelines.

### Goals:

* Catch vulnerabilities and design flaws early, before they hit production
* Reduce friction by making security part of existing engineering workflows
* Empower dev teams with self-service security tools and guardrails

#### Personal

* Aims to build credibility as a trusted security advisor within engineering
* Likes to stay current on emerging OSS security tooling and secure development patterns

#### Project

* Bake security requirements into product backlogs from day one
* Introduce threat modelling and dependency scanning in early sprints

#### Organization

* Reduce security incident frequency and remediation costs
* Align with compliance frameworks like ISO
* Drive adoption of open source security tooling across product teams

### Challenges:

* Dev teams tend to view security as overhead unless it’s tightly integrated
* Vulnerability remediation is often reactive, not proactive
* Hard to get org-wide visibility on open source usage and supply chain risk
* Tooling overload: multiple vendors, fragmented OSS solutions

### How the OpenSSF can help:

* Highlight security standards (e.g., SLSA, SAMM) that map to Boyd’s compliance needs

* Build integrations with common CI/CD systems so enforcement is baked in

* Create case studies showing how product security engineers like Boyd can operationalize OpenSSF tooling at scale

* Participate in working groups that blend AppSec, DevSecOps, and OSS security best practices

---

## Name: Guinevere GRC (Security Governance Lead)

### Role:
- Security Policy Lead at an international research institute

### Background:
- Guinevere bridges the world of policy and engineering. She’s the one defining what “secure enough” means for dev environments, tools, and internal infra. She collaborates across compliance, security, and platform teams to keep things aligned and reduce risk without crushing velocity. Yasmine’s been watching OpenSSF’s policy and best practices work closely—and would love to contribute when she can.

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
- Policy-as-code is powerful but not adopted enough

### How the OpenSSF can help:
- Share reusable policy templates for securing dev environments and tooling
- Highlight projects that ship with secure defaults
- Build bridges between governance pros across orgs to share real-world insights

---
