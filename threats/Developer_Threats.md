The following threats have been identified to be in scope that threaten the [Secure Developer](https://github.com/ossf/toolbelt/blob/main/capabilities/Secure_Developer_Capability.md) capability:

## TBT-1100 (Category) Actor merges malicious commit/regression/dependency
- TBT-1110 - Malicious Developer
- TBT-1120 - Untrained Developer
- TBT-1121 - Lack of knowledge of security primitives affecting the code they produce
- TBT-1122 - Incorrect or ineffective use of security technologies or tools
- TBT-1123 - Lack of code documentation (or broken, incorrect, misleading)
- TBT-1124 - Lack of awareness of privacy-by-design and security-by-design principles leads to data exposure
- TBT-1130 - Unverified/unauthenticated developer
- TBT-1140 - Unchecked anonymous/community commit merged

|             |                                                            |  
| :------:    | :--------------------------------------------------------: | 
|    TBT-1100 |    Actor merges malicious commit/regression/dependency     | 
| Description | An actor (either authorized or unauthorized) writes and attempts to merge software or add a dependency either through unintentional error or with malicious intent |  
| Potential Impact | The introduction of malicious software into a project’s course code and/or dependencies may introduce downstream consumers to unexpected and/or unwanted behaviour, make them susceptible to security vulnerabilities and or malware that could lead to the exfiltration of sensitive data, corruption of the integrity of sensitive data, or cause a loss of availability to systems and resources |      
|    Controls     |         |
|    Example(s)     |         |
|    References     | 1.) OpenSSF End User Working Group’s [Threat Model](https://docs.google.com/document/d/1lLCsT0a5vp6FcvquWPzx8AzhFMORyw-4rd9WSyUO9zI/edit) 2.) Compromise a legitimate upstream project (C-1) -AV-001 in the seminal paper [Taxonomy of Attacks on Open-Source Software Supply Chains](https://ieeexplore.ieee.org/abstract/document/10179304) 3.) Confirmed malicious packages [reported by OSV](https://osv.dev/list?q=MAL)        |



  
## TBT-1200 (Category) Unauthorized Actor compromises legitimate account
- TBT-1210 - Compromised Developer Account (impersonation) 
- TBT-1220 - Developer under duress
- TBT-1230 - “Tail-gating”

|             |                                                            |
| :--------:  | :--------------------------------------------------------: | 
|    TBT-1200 |  Unauthorized Actor compromises legitimate account    | 
| Description | An unauthorized actor through some malicious act compromises a valid developer's account or credentials with the intent to exfiltrate sensitive data or to make unauthorized changes to the project's software, dependencies, or configuration.  |  
| Potential Impact |   |      
|    Controls     |         |
|    Example(s)     |         |
|    References     |

## TBT-1300 (Category) Failure in tooling/configuration/process allows insertion of malicious software into codebase
- TBT-1310 - Security scanning tools not properly configured/ignored
- TBT-1320 - Project has no tooling/testing infra
- TBT-1330 - Compromised developer signing key
- TBT-1340 - Lack of 2nd developer for peer review of commits prior to merge
- TBT-1350 - Lack of threat model for software introduces architectural or dependency weaknesses or vulnerabilities

|             |                                                            | 
| :------:    | :--------------------------------------------------------: | 
|    TBT-1300 |    Failure in tooling/configuration/process allows insertion of malicious software into codebase    | 
| Description | Deficiencies in or absense of appropriate the project's tooling, configuration, or proesses allows unchecked errors and potentially malicious software to be committed into the project's codebase and can be masquaraded as legitimate and authorized changes.  |  
| Potential Impact |   |      
|    Controls     |         |
|    Example(s)     |         |
|    References     | 

## Assumptions
- Developer can be a project maintainer, contributor, or community member
- Developers have the ability to create new code, edit older code, integrate new 3rd party components or dependencies.  
- Only certain developers (maintainers) have the ability to push commits into main branch of software
- Initiation of a project may not start from a template or uses flawed template
- Not all projects include basic security capabilities/automated checks at initiation

