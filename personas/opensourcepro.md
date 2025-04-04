# Open Source Professional (OSPO)


### Name: Siddharth the Supplier

#### Role: 
- Siddharth’s company creates a commercial product that heavily uses open source software and has hundreds of dependencies on assorted OSS libraries.
- Siddharth’s engineers contribute features and bug fixes back upstream to many of the packages used within their product and are active project community members in the projects they deem most critical to their solutions.
- Based on their community contributions and project roles, they sometimes are included in CVD efforts for a few of their OSS components, but not all (not even a large number).  These roles allow them to share pre-embargo information ahead of public disclosure internally to prepare so their customers can have patches available at the time of public disclosure. 

#### Background:
- Suppliers may or may not understand all of the third-party components and open source software included in their commercial offerings.
- Suppliers typically will support some form of platform or commercial product they license or provide support/subscriptions for.
- Suppliers may or may not be involved in upstream projects they consume and support to a downstream, providing bug fixes upstream.
- Suppliers may or may not be within the circle of trust to receive pre-embargo disclosures to help support downstream.
- Suppliers have their own business goals and objectives that may differ from upstream.  The Supplier’s customers look to the Supplier to provide support/bugfixes/vulnerability management for all components within the solution they provide regardless of their ability to influence upstream.
- Suppliers have their own internal SDL practices.
- Suppliers need to be conducting due diligence on their component suppliers.

#### Goals:
- I want to understand upstream oss & third-party components used within my solution.
- I need to react to customer inquiries and demand for updates for all components within my solution.
- I would like to participate and have influence in upstream communities that matter to me and my customers.
- I provide support for my solution that may be longer than what my upstream components provide.  I need to decide how to manage that situation in financially responsible ways.
- Using OSS helps me extend my engineering capabilities and helps spread the burden of support across all community members/participants.  Ideally more suppliers follow me and participate in these communities as well.

#### Challenges:
- I have Regulatory Obligations and Customer Requirements for my solution that may or may not be met by my upstream providers that I need to provide to my downstream.
- I don’t understand all of my upstream components, how those communities operate, nor how to stay updated with upstream changes.
- Upstream components I use release bug fixes and vulnerability patches too frequently, and do not match my release schedule.  Sometimes upstream releases breaks API/ABI compatibility of my solution, barring me from quickly implementing them.
- Not enough other suppliers participate in the software projects that I use, either forcing me to shoulder more of the burden or updates are not done by the community due to lack of resources or prioritization.
- My Regulators and Customers are putting an ever-increasing burden on me to comply with laws, evidentiary requirements, and vulnerability fixes.  
- Why upstream has no plans or bandwidth to make updates/fixes - As downstream, what are my options?
- I may choose to not be completely transparent about my practices and components and desire to just meet the bare minimum requirements to meet my legal and regulatory obligations

#### How the OpenSSF can help:
Projects like Scorecard can help me evaluate the OSS components I use in my solution.
Frameworks like SLSA & S2C2F help me understand how my upstream components are developed, composed, delivered and things I need to do as I am ingesting them.
My developers need to understand secure application development and secure supply chain practices so we can follow expected industry best practices like the output of the Best Practice working group and the secure development training.
I need to understand when fixes and vulnerability patches are provided upstream and then analyze the impact to my particular implementation of that software and how that would affect my customers like OSV, OpenVEX, and the CVD Guides from the Vuln Disclosure working groups


##### Name: Sammy the Startup Supplier (forthcoming)
- Goes fast, breaks stuff
  
##### Name: Larry the Legacy Supplier (forthcoming)
- Slow and steady, traditional vendor of a large software system with long development cycles. The resulting software system is often probably critical to the company / country, so the impact of errors can be largeare extremely concerning, leading to general risk aversion. It’s also probably large with a lot of technical debt, and the current maintainers may not be familiar with parts of the system (as their previous maintainers have left), making changes hard and costly.

### Name: Carl the Consumer

#### Role:
- Consumers utilize open source software to create software and/or other products which includes open source software as building blocks
- Consumers primarily ingest open source software, but may also contribute features and security improvements, yet in significantly lower volumes than ingesting open source software

#### Background:
- Consumers can be commercial and non-commercial entities
- Commercial entities are subject to regulatory requirements with respect to product security
- Consumer can also be producers

#### Goals:
- I want to determine and understand the security posture of the open source software I consume in a scalable and meaningful manner to
- make sure that the (software) products I build are compliant to regulatory requirements
- manage the risks associated with consuming open source software in my products
- to guide meaningful upstream contributions to improve the security posture of the software I rely on

#### Challenges:
- Open source projects differ widely in terms of security qualities 
- It is difficult to assess and understand the security qualities of open source software in a meaningful manner due to the wide range of different (open source) development practices
- Programming languages, tools, source code management and hosting, governance and community structure (company backed projects, foundation based projects, individual maintainer-based projects)
- A supply chain inherently involves multiple entities (e.g., maintainer/supplier and consumer per supply chain link) which need to interact utilize interoperable means for conveying information

#### How the OpenSSF can help: (incomplete, we agreed to work on this later)
- Provide an environment for developing tools for (automatically) assessing and/or improving the security quality of open source projects or for developing improvement proposals for existing tools
- Provide guidelines and recommendation for methods of exchanging information, fostering adoption of interoperable methods
- Provide data (sources) which provide an insight into the security qualities of open source projects

