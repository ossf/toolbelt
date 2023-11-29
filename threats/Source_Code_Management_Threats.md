The following threats have been identified to be in scope that threaten the [Secure Source Code Management (SCM) system](https://github.com/ossf/toolbelt/blob/main/capabilities/Secure_Source_Code_Management_Capability.md) capability:

## TBT-3100 (Category) Actor pushes malicious or vulnerable code to repo and/or deletes code
- TBT-3110 - Unauthenticated user pushes code
- TBT-3120 - Unauthorized user pushes/changes/deletes code
- TBT-3130 - Malicious actor impersonates authorized user
- TBT-3140 - Loss of access (DoS)
- TBT-3150 - Sign commit, and validate what changed since hash

|             |                                                            |  
| :------:    | :--------------------------------------------------------: | 
|    TBT-3100 | Actor pushes malicious or vulnerable code to repo and/or deletes code   | 
| Description |   |      
|    Controls     |         |
|    Example(s)     |         |
|    References     |  |


## TBT-3200 (Category) - Source code repo configuration- Actor implements inadequate repo permissions which leads to information disclosure, altered integrity, or loss of availability 
- TBT-3210 - Malicious actor changes SCM repo configuration to allow unauthorized behavior - E.g. unrecorded changes
- TBT-3220 - Loss of privacy for developers  - Mitigate by creating using a configuration pattern / template
- TBT-3230 - Authentication/authorization. Use 2FA at the repo level
- TBT-3240 - Policy Agent: Pre-commit hooks. 
- TBT-3250 - Commit logs. Make sure logs are created and can’t be tampered with

|             |                                                            |  
| :------:    | :--------------------------------------------------------: | 
|    TBT-3200 | Source code repo configuration- Actor implements inadequate repo permissions which leads to information disclosure, altered integrity, or loss of availability    | 
| Description |   |      
|    Controls     |  Mitigations - to get access to premier features, use a merkle tree to have logs by default.
       |
|    Example(s)     |         |
|    References     |  |

## TBT-3300 (Category) - An out of band actor directly manipulates SCM contents

|             |                                                            |  
| :------:    | :--------------------------------------------------------: | 
|    TBT-3300 | An out-of-band actor directly manipulates SCM contents  | 
| Description |Malicious actor tampers with code outside of the SCM system’s control plane.  E.g. get access directly to the server   |      
|    Controls     |         |
|    Example(s)     |         |
|    References     |  |

## TBT-3400 (Category) Lack of resilient/redundant infrastructure leads to Denial of Service of the developer’s workstation, dependent software, or other infrastructure used within the pipeline that hinders the developer from writing an/or promoting code

|             |                                                            |  
| :------:    | :--------------------------------------------------------: | 
|    TBT-3400 | Lack of resilient/redundant infrastructure leads to Denial of Service of the developer’s workstation, dependent software, or other infrastructure used within the pipeline that hinders the developer from writing an/or promoting code
   | 
| Description |   |      
|    Controls     |         |
|    Example(s)     |         |
|    References     |  |

## TBT-3500 (Category) Code quality requirements not being met
- TBT-3510 - Undocumented or unknown dependencies to communicate the recipe for build software. Store an SBOM - Know all components and dependencies needed to use the software. If had a diff, could know if something in source code was altered in a change of custody
- TBT-3520 - Victim of typosquatting, scanner against SBOM could detect that
- TBT-3530 - Code quality from SCM perspective

|             |                                                            |  
| :------:    | :--------------------------------------------------------: | 
|    TBT-3500 | ode quality requirements not being met  | 
| Description |   |      
|    Controls     |         |
|    Example(s)     |         |
|    References     |  |

## Assumptions
- Source Code Management can be performed on a developer workstation, within a shared SCM server, or in a cloud-based environment
- SCM can be a shared environment where multiple parties have access to and that should be appropriately managed
- Should not assume developers have a best practice template with which they using to start
- Dev may not have an entity that configures & manages source code repo
- Dev may not have understanding of downstream consumers needs and requirements for configurations
