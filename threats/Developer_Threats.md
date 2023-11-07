The following threats have been identified to be in scope that threaten the Secure Developer capability:

## (Category) Actor merges malicious commit/regression
- Malicious Developer
- Untrained Developer
-- Lack of knowledge of security primitives affecting the code they produce
-- Incorrect or ineffective use of security technologies or tools
-- Lack of code documentation (or broken, incorrect, misleading)
-- Lack of awareness of privacy-by-design and security-by-design principles leads to data exposure
- Unverified/unauthenticated developer
-- Unchecked anonymous/community commit merged
## (Category) Unauthorized Actor compromises legitimate account
- Compromised Developer Account (impersonation) 
- Developer under duress
- “Tail-gating”

## Assumptions
- Developer can be a project maintainer, contributor, or community member
- Developers have the ability to create new code, edit older code, integrate new 3rd party components or dependencies.  
- Only certain developers (maintainers) have the ability to push commits into main branch of software
