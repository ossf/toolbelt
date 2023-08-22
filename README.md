# The OpenSSF Security Toolbelt (formally known as the Sterling Toolchain)


We are a group of community members working to help define the vision and execution of the OpenSSF's Security Toolbelt initiative that is focused on helping all participants and consumers in the open source software ecosystem work more securely.

We are part of the [BEST Working Group](https://github.com/ossf/wg-best-practices-os-developers).

### Motivation

The open source software ecosystem has incredible diversity and variation of practice.  The Security Toolbelt seeks to provide consistent guidance, processes, and tools that enable open source developers to create amazing software, securely, and allow all partipants and consumers of that downstream supply chain to be able to understand the security qualities of how that software was written, assembled, and delivered to them, as well as concrete things downstream can do to implement this software securely.

## Mission

Assemble a “sterling” collection of capabilities (**software frameworks, specifications, and human and automated processes**) that work together to **automatically list, scan, remediate, and secure the components flowing through the software supply chain** that come together as software is written, built, deployed, consumed, and maintained. Each piece of the collection will represent an **interoperable** link in that supply chain, enabling adaptation and integration into the major upstream language toolchains, developer environments, and CI/CD systems. The scanning, remediating, and listing steps will be focused on the core security principles of **security by design** and **secure settings by default**, and the data they depend on will be **constantly updated based on observed threats**. 

## Vision

A world where **every software package is verifiably trustworthy**, across all major open source projects and ecosystems, meaning fewer security defects across the software landscape, reduction of the costs and damages when remediating the defects that still happen, and support for the growing use of audits and regulatory requirements for secure development and deployment.

## Strategy

To achieve the mission and vision of the Toolbelt initiative, the following strategy will be followed
<ol>
<li>Expose critical security actions through the definition of specific use cases that are needed to harden the software factory from code through deploy.</li>
<li>Define barriers to the adoption of security tooling in the software factory.</li>
<li>Identify and address gaps in tooling that are not addressed by existing open-source and closed source security tooling categories.</li>
<li>Create a coalition of open-source and closed source contributors to define a common security tooling vocabulary.</li> 
<li>Support existing tooling integration efforts, or build a common integration layer between security tooling that can be easily integrated into developer practices, regardless of language/platform.</li> 
<li>Drive and then monitor the adoption of key pieces of the toolbelt into upstream language ecosystems. Where they succeed we will document and aim to make repeatable; where they underwhelm, we will analyze why. Where they fail, we will look for fixes or alternatives.</li>
<li>To iterate a scalable system, we will work with the Alpha-Omega project to identify potential POC teams to test out approaches, including projects with a single maintainer.</li>
</ol>

What the strategy will not include:
<ul>
<li>A strict list of security tooling.</li> 
<li>This strategy will not be a “big tent” of all possible tools and approaches, but a lean collection of strictly the most important pieces we expect the toolchains of the world to adopt. This must still be vendor-neutral.</li>
</ul>

## Roadmap

At each stage of this roadmap, we will revise and refine our plans based on what we have learned.
<ol>
<li>The OpenSSF will develop a clear set of **capabilities**, **personas**, **use cases**, **taxonomy**/**shared language**, and **threat models** that span the entirety of the software supply chain.</li>
<li>Align controls to the threats identified and with **existing control frameworks**, e.g. [NIST SP800-218](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-218.pdf). Where existing control frameworks are insufficient, we will propose new controls.  Based on that, **develop a map** of the existing products, processes, templates and other IP (inside and outside the OpenSSF) that act as “controls”, that reduce the risks identified by these use cases and threat models.</li>
<li>Perform a **market survey** to determine what products, patterns or techniques could achieve the control requirements identified in (2), noting where there are gaps.</li>
<li>**Identify functional gaps, integration challenges, and opportunities to simplify** by looking at the links between these pieces. </li>
<li>**Fill those gaps** by adapting interfaces/existing tools/processes/templates or driving the development of new interfaces/tools/processes/templates. Address the integration challenges by working with the existing pieces to get to e.g. better APIs. Develop a shared vocabulary to avoid confusion between the parts of the Toolbelt.</li>
<li>Validate the approach by **working with selected OSS** projects and modify it as necessary.</li>
<li>Document everything to sufficient degree as to **develop a certification mark** (or series of marks) that verify conformant toolchains and other supply chain components, and a dashboard or other risk measurement frameworks that drive a “race to the top” among toolchains and ecosystems.</li>
<li>Develop an **outreach strategy** to initiate adoption and build awareness of the toolbelt solution. The outreach should be persona / platform based.</li>
</ol>

Original working [document](https://docs.google.com/document/d/1k-0ReRSXEOIT8FRVbwNMe0BJ-QUvn-0c0hfFY-f4QzA/edit)

## Scope Initiatives, Projects, Working Groups, Special Interest Groups, and other collaborative efforts supported by the OpenSSF

<TBD>
  
## Current Efforts

The group is developing a list of 
- [capabilities](https://docs.google.com/document/d/1DtSaj2avvKCdXLcWu6W4-Np7uKVizLCTmI0KWxqVitE/edit)
- [use cases](https://docs.google.com/document/d/10oFJrMcIkKb0X7Bw1EwrN1w_wbyVUj0EAUswXMp73lQ/edit#heading=h.pmnr72fd8v8b)
- [threats](https://docs.google.com/document/d/1RG4_JeUWlx1AMHh6XAhEuVhyoaYqfiBSr789HTnSVEM/edit#heading=h.p2mmdnf7yli9) and
- [patterns]()

## Prior Work

- [Sterling Toolchain Concept](https://docs.google.com/document/d/1z4YxuT6yzbgrNlUpgTbJhuKv5ngdsd6O8Dz5yRTepgs/edit#)

## Get Involved 
We currently are soliciting ideas around the design, implementation, and evangelism of the Security Toolbelt. Questions and feedback are welcome on our mailing list, slack channel, or as an issue filed here in our repo.

- Official communications occur on the [The Security Toolbelt Mailing List.](Openssf-sig-sterling-toolchain@lists.openssf.org)
- Manage your subscriptions to [Open SSF mailing lists.](https://lists.openssf.org/g/main/subgroups)
- Security Toolbelt [Slack channel](https://openssf.slack.com/archives/C057BN7K19B)

## Quick Start

Areas that need contributions :  
- Where to file issues: Issues can be filed here in our GitHub [repo](https://github.com/ossf/Diagrammers-Society/issues).

## Meeting times

- Every Tuesday @ 12:00pm EST OpenSSF [Community Calendar](https://calendar.google.com/calendar?cid=czYzdm9lZmhwNWk5cGZsdGI1cTY3bmdwZXNAZ3JvdXAuY2FsZW5kYXIuZ29vZ2xlLmNvbQ)
- Meeting [Minutes](https://docs.google.com/document/d/1H3Nk0PwmylLg5F7pqrIvyKzTyXAll0-f50B7DdqOh4A/edit#heading=h.9m0zi4b0wnne)

## Governance

The [CHARTER.md](https://github.com/ossf/Diagrammers-Society/blob/main/CHARTER.md) outlines the scope and governance of our group activities.

    Lead name : TBD
    Co-Lead name: TBD

### Project Maintainers
    TBD

### Project Collaborators

    [Andrea Frittoli, IBM](https://github.com/afrittoli)
    [Arnaud Le Hors, IBM](https://github.com/lehors)
    [Behan Webster, The Linux Foundation](https://github.com/)
    [Brandon Mitchell, IBM](https://github.com/sudo-bmitch)
    [Brian Behlendorf, The Linux Foundation](https://github.com/}
    [Brian Wagner, IBM](https://github.com/wags007)
    [Christopher "CRob" Robinson, Intel](https://github.com/SecurityCRob)
    [Daniel Appelquist, Synk](https://github.com/Torgo)
    [David A Wheeler, LF/OSSF](https://github.com/david-a-wheeler)
    [Georg Kunz, Ericsson](https://github.com/}
    [Jacques Chester, independent](https://github.com/jchester)
    [Jay White, Microsoft](https://github.com/camaleon2016)
    [Jeff Borek, IBM](https://github.com/jtborek)
    [Jon Meadows, Citi](https://github.com/}
    [Josh Clements, Analog Devices](https://github.com/}
    [Joshua Lock, Verizon](https://github.com/}
    [Kris Borchers, independent](https://github.com/}
    [Marcela Melara, Intel](https://github.com/marcelamelara)
    [Matt Rutkowski, IBM](https://github.com/mrutkows)
    [Melba Lopez, IBM](https://github.com/}
    [Michael Leiberman, Kusari](https://github.com/mlieberman85)
    [Phil Estes, AWS](https://github.com/estesp)
    [Ryan Ware, Intel](https://github.com/ware)
    [Sal Kimmich, EscherCloud AI](https://github.com/salkimmich)
    [Sarah Evans, Dell](https://github.com/sevansdell)
    [Steve Taylor, Deployhub/Ortelius/Pyrsia](https://github.com/}
    [Tom Hennen, Google](https://github.com/TomHennen)
    [Tracy Ragan, Deployhub/Ortelius/CDEvents](https://github.com/}
    
### Project Contributors


#
**Intellectual Property**

In accordance with the [OpenSSF Charter (PDF)](https://charter.openssf.org/), work produced by this group is licensed as follows:

[TODO: Select below the applicable license(s), delete those that don't apply, and update the LICENSE file accordingly. For specification development refer to the specific instructions on the [Community Specification Getting Started page](https://github.com/CommunitySpecification/1.0/blob/main/..Getting%20Started.md).

Note that for source code, instead of Apache, you may choose to use the MIT License available at https://opensource.org/licenses/MIT. Otherwise, no other license than those listed here may be used without approval from the Governing Board.]

1. Software source code
* Apache License, Version 2.0, available at https://www.apache.org/licenses/LICENSE-2.0;
2. Data
* Any of the Community Data License Agreements, available at https://www.cdla.io;
3. Specifications
* Community Specification License, Version 1.0, available at https://github.com/CommunitySpecification/1.0
4. All other Documentation
* Creative Commons Attribution 4.0 International License, available at https://creativecommons.org/licenses/by/4.0/

**Antitrust Policy Notice**

Linux Foundation meetings involve participation by industry competitors, and it is the intention of the Linux Foundation to conduct all of its activities in accordance with applicable antitrust and competition laws. It is therefore extremely important that attendees adhere to meeting agendas, and be aware of, and not participate in, any activities that are prohibited under applicable US state, federal or foreign antitrust and competition laws.

Examples of types of actions that are prohibited at Linux Foundation meetings and in connection with Linux Foundation activities are described in the Linux Foundation Antitrust Policy available at http://www.linuxfoundation.org/antitrust-policy. If you have questions about these matters, please contact your company counsel, or if you are a member of the Linux Foundation, feel free to contact Andrew Updegrove of the firm of Gesmer Updegrove LLP, which provides legal counsel to the Linux Foundation.
