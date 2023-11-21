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

|             |                                                            |   ID     |
| :------:    | :--------------------------------------------------------: | :-------:|
|    Name     |    Actor merges malicious commit/regression/dependency     | TBT-1100 |
| Description | An actor (either authorized or unauthorized) writes and attempts to merge software or add a dependency either through unintentional error or with malicious intent |         |
| Potential Impact | The introduction of malicious software into a project’s course code and/or dependencies may introduce downstream consumers to unexpected and/or unwanted behaviour, make them susceptible to security vulnerabilities and or malware that could lead to the exfiltration of sensitive data, corruption of the integrity of sensitive data, or cause a loss of availability to systems and resources |      
|    Controls     |         |   |
|    Example(s)     |         |   |
|    References     | 1.) OpenSSF End User Working Group’s [Threat Model](https://docs.google.com/document/d/1lLCsT0a5vp6FcvquWPzx8AzhFMORyw-4rd9WSyUO9zI/edit) 2.) Compromise a legitimate upstream project (C-1) -AV-001 in the seminal paper [Taxonomy of Attacks on Open-Source Software Supply Chains](https://ieeexplore.ieee.org/abstract/document/10179304) 3.) Confirmed malicious packages [reported by OSV](https://osv.dev/list?q=MAL)        |   |



  
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

