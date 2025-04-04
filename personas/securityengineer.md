
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
