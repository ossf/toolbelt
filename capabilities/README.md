# Purpose 
To define a series of desired capabilities the OSSF Security Toolbelt would work towards documenting/delivering/showcasing aligning with the documented MVSR the Toolbelt group has collaborated on.  
From the agreed-upon list of desired capabilities, further work and analysis will be done to identify reference patterns, architecture, patterns in implementation, anti-patterns, required inputs/outputs (aka “signals”), and other desired data for maturation of the Security Toolbelt initiative.

# Capabilities

<img align="top" src="https://github.com/ossf/Diagrammers-Society/blob/main/SecurityToolbelt/files/Toolbelt%20Capabilities.png">

## Capabilities desired from the Upstream Secure Software Factory
### Code & Pre-Build
#### Secure Developer
It is desirable that developers have knowledge of how to develop software securely, that they understand common coding errors and patterns of behaviour that lead to security vulnerabilities, and have the means to highlight their security expertise.

#### Secure Development Environment
It is desirable that developers have access to and use secure tools to create and test software. This would include various security tools such as SAST, fuzzers, etc.

#### Secure Dependency Selection
It is desirable that developers select dependencies to select secure and sustainable projects and ensure they’re ingesting the intended components (countering typosquatting).

#### Secure Source Code Management
It is desirable that developers and projects store source code for their software in secured repositories that help manage and track the integrity of that code.

### Build
#### Secure CI/CD - Build System
It is desirable that developers and projects use secure build systems that continuously integrate and build authorized software, and also leverage secure tools for automation of repeated tasks.

### Post build
#### Secure Publication/Distribution
It is desirable that developers and projects use secure methods and tools to publish and distribute their production-ready software to their downstreams.

### Post publish

## Capabilities desired from Downstream Secure Integration/Operations Facility
### Secure Ingestion
It is desirable that downstream consumers of upstream open source software have effective signaling and methods to identify and evaluate the security quality of open source software, dependencies, and libraries that they integrate into their own operations and software.

### Secure Implementation
It is desirable that downstream consumers have sufficient instructions and tools to implement upstream software securely into their own operations and software.

### Secure Maintenance
It is desirable that downstream consumers have the means to be informed of updates and changes to upstream software so that they can effectively maintain and operate that software in their own operations and software during the software’s supported lifecycle.
	
## Cross-Cutting Capabilities
### Supply Chain Metadata Storage
It is desirable for an organization implementing a secure SDLC to have a place to store, query, and analyze metadata pertinent to the prevention, detection, and remediation of supply chain security issues.

### Supply Chain Control Plane
It is desirable for an organization implementing a secure SDLC to have a centralized place to configure and manage the other capabilities to ensure consistent policy enforcement.
