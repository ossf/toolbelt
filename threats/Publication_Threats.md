The following threats have been identified to be in scope that threaten the [Publication/Distribution](https://github.com/ossf/toolbelt/blob/main/capabilities/Secure_Publication-Distribution_Capability.md) capability:

## TBT-5100 (Category) Actor pushes malicious or vulnerable package to repo
- TBT-5110 - Unauthenticated artifact is pushed to package/artifact repo
- TBT-5120 - Unverified artifact is pushed to package/artifact repo
- TBT-5130 - Vulnerable/malicious software not being regularly checked or removed

|                  |                                                            |  
| :------:         | :--------------------------------------------------------: | 
|    TBT-5100      |    Actor pushes malicious or vulnerable package to repo     | 
| Description      | An Actor either with malice or by mistake publishes a malicious or vulnerable package to th publically available download sites.  |  
| Potential Impact |         |      
|    Controls      |         |
|    Example(s)    |         |
|    References    |         |


## TBT-5200 (Category) (Private only) Unauthorized actor pulls package from private repo - Information Disclosure
|             |                                                            |  
| :------:    | :--------------------------------------------------------: | 
|    TBT-5200 |    Unauthorized actor pulls package from private repo   | 
| Description | An unauthorized actor publishes packages, data, configs from a private repository to a public one.  |  
| Potential Impact |   |      
|    Controls     |         |
|    Example(s)     |         |
|    References     |     |

## TBT-5300 Publisher fails to provide means to help mitigate “Dependency Confusion” / typosquatting, etc.
|             |                                                            |  
| :------:    | :--------------------------------------------------------: | 
|    TBT-5300 |    Publisher fails to provide means to help mitigate “Dependency Confusion” / typosquatting, etc.     | 
| Description | Publisher fails to provide means to mitigate "Dependency Confusion and typosquatting attacks and consumer download unauthentic and potentially malicious software instead of valid versions. |  
| Potential Impact |   |      
|    Controls     |         |
|    Example(s)     |         |
|    References     |     |

## TBT-5400 (Category) Actor compromises repository packages, metadata, or infrastructure
- TBT-5410 - Rollback, Freeze, Fast Forward Attacks
- TBT-5420 - Selectively provide malicious code to targeted consumers
- TBT-5430 - CDN attacks/stale CDN
  
|             |                                                            |  
| :------:    | :--------------------------------------------------------: | 
|    TBT-5400      |    Actor compromises repository packages, metadata, or infrastructure     | 
| Description      |  An actor is able to access and compromises public repositories, metadata, or infrastructure to make unauthorized changes.   |  
| Potential Impact |         |      
|    Controls      |         |
|    Example(s)    |         |
|    References    |         |
 
## Assumptions
- Projects may host files/source in different systems than the publication platform
- Packages may be acquired directly from a project, from a distributor (ala Linux Distros), or other 3rd party
- Consumers choosing to directly download source code and perform compile/build/distribution steps themselves are subject to the applicable threats to those stages
- Project documentation should provide authoritative sources, checksums, and procedures to leverage the project’s software


