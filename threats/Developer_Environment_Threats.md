The following threats have been identified to be in scope that threaten the Secure Developer Environment capability:

## TBT-2100 (Category) Failure to perform Cyber Hygiene regularly creates Insecure development environment
- TBT-2110 - Missing or not up to date tools (e.g.AV/EDR leads to Malware infection)
- TBT-2120 - Unpatched Dev Env with exploitable vulns
- TBT-2130 - Use of software and tools with vulnerabilities; harden/patch software and tools
- TBT-2140 - Use of Operating system with vulnerabilities; harden/patch OS
- TBT-2150 - Insecure configurations, e.g. unprotected cryptographic secrets

|             |                                                            |  
| :------:    | :--------------------------------------------------------: | 
|    TBT-2100 | Failure to perform Cyber Hygiene regularly creates Insecure development environment   | 
| Description | Lack of awareness of and implmention of common security best practices leads to the developer writing code in a vulnerabile ad insecure environment that can lead to exploitation.  |  
| Potential Impact | Developer Environment (Dev Env) susceptible to insecure and vulnerabile configurations that allow attack to gain presense within the environment.  Dev Env has unpatched and exploitable vulnerabilities within the hardware and software that allow exploitation by attacker.  Lack of proper due dilligence and process allow attacker to covertly stay resident within the environment and conduct further acttivities.  |      
|    Controls     |         |
|    Example(s)     |         |
|    References     |  |

## TBT-2200 (Category) Failure to analyze/validate code and configurations leads to insecure software
- TBT-2210 - Missed analysis (e.g. static configuration analysis, 
- TBT-2220 - symptom could be missing SCA tool tools
- TBT-2230 - Symptom could be misconfigured tool
- TBT-2340 - Symptom could be using the wrong tool (unintended purpose, or tool not capable of accomplishing the purpose)

|             |                                                            |  
| :------:    | :--------------------------------------------------------: | 
|    TBT-2200 |  Failure to analyze/validate code and configurations leads to insecure software       | 
| Description | Project has either insuffient, misconfigured, or no tooling to conduct automated security scanning which leads to errors and/or malicious software entering the project's codebase.  |  
| Potential Impact | Known vulnerabilities or vulnerable code patterns are a committed into the software that allows dowstream exploitation.  Project has false sense that tooling is working while it is misconfigured and not effectively notifying about vulnerabilities within the code.     |      
|    Controls     |         |
|    Example(s)     |         |
|    References     |  |

## TBT-2300 (Category) Reliance on 3rd Party Code or generative tools (AI tool assistants, auto-code generation utilities) without understanding/critique code output

|             |                                                            |  
| :------:    | :--------------------------------------------------------: | 
|    TBT-2300 | Reliance on Code copied from unvalidated sources or through code generation (AI tool assistants, auto-code generation utilities) without understanding/critiquing the code output        | 
| Description | Through the use of coding assistance tools, such as AI/ML tools, or from copying code snippets from repositories, such as StackOverflow, unverfiied and potentially regressive and malicious code enters the project's codebase withut any controls to prevent or identify such use.  |  
| Potential Impact | Developer merges potentially unintentionally vulnerable code into the project.  Developer merges intentionally malicious code into the project. Coding assistant tools trained with buggy or incorrect patterns and produces vulnerable code that is ingested and merged into the project|      
|    Controls     |         |
|    Example(s)     |         |
|    References     |  |

## Assumptions
- Development environment can range from an unmanaged local IDE on a laptop/workstation, a local installation of development SCM and CI tools, a corporate-controlled and managed workstation, to a virtualized machine in a corporate VDE or any combination.
