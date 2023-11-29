The following threats have been identified to be in scope that threaten the [Secure Build/CI](https://github.com/ossf/toolbelt/blob/main/capabilities/Secure_Build%2BCI_Capability.md) systems capability:

## TBT-4100 (Category) Build environment pushes/pulls vulnerable or malicious code
- TBT-4110 - Deployments not standardized across teams in environment
- TBT-4120 - Tampering with build workload -- This can be done by a malicious actor actively execing/sshing into the container/server running a workload and tampering with it or it can be done by a malicious build environment like a container image or build environment
- TBT-4130 - Lack of security tooling in pipeline
- TBT-4140 - Authorized actor runs pipelines out of compliance with policy

|             |                                                            |  
| :------:    | :--------------------------------------------------------: | 
|    TBT-4100 | Build environment pushes/pulls vulnerable or malicious code | 
| Description | Insufficient checks, tooling, and automation exists to prevent malicious code from being brought into the build system.   |  
| Potential Impact |   |      
|    Controls     |         |
|    Example(s)     |         |
|    References     |  |



## TBT-4200 (Category) Build environment pushes/pulls vulnerable or malicious dependencies

|             |                                                            |  
| :------:    | :--------------------------------------------------------: | 
|    TBT-4200 | Build environment pushes/pulls vulnerable or malicious dependencies  | 
| Description |Insufficient checks, tooling, and automation exists to prevent malicious dependencies from being brought into the build system.     |  
| Potential Impact |   |      
|    Controls     |         |
|    Example(s)     |         |
|    References     |  |

## TBT-4300 (Category) Actor introduces malicious or inadequate security behavior into a pipeline

- TBT-4310 - Malicious build gets access to secrets, especially signing secrets
- TBT-4320 - Malicious CI/CD step reaches out to network to download malicious payload
- TBT-4330 - Noisy output
- TBT-4340 - Malicious, vulnerable, or misconfigured CI/CD software
- TBT-4350 - Malicious actor hijacks otherwise reliable package that is used commonly in CI/CD pipelines
- TBT-4360 - Actor tampers with orchestration of workloads -- This can be a malicious authorized admin or an unauthorized actor who gets access to the control plane
- TBT-4370 - Critical steps skipped or missed in build/test procedure

|             |                                                            |  
| :------:    | :--------------------------------------------------------: | 
|    TBT-4300 | Actor introduces malicious or inadequate security behavior into a pipeline | 
| Description | An actor exploits the Build/CI system to introduce malicious software into the pipeline.   |  
| Potential Impact |   |      
|    Controls     |         |
|    Example(s)     |         |
|    References     |  |


## Assumptions
- Script-driven processes are not managed by change-management/review and are not in source control
- The build is separate from the development infra
- The CI/CD system is not part of the production environment


