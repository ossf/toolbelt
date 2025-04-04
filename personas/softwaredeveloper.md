# Software Developer/Maintainer Personas

## Name: Debbie the Downstream contributor

### Role: 
- Staff Engineer at big tech company
- 
### Background: 
- Mary writes open source software for a large tech firm. She has had both jobs focused on open source software as well as closed source software. She is responsible for maintaining a popular open source project. Her maintainer status on the project is not tied to her job, but she is paid by her company to work on the project.
- 
### Goals: 
- Mary has multiple goals tied to herself personally, the project, and her job. For herself, she wants to not end up overloaded with work, and she wants to be seen as a good member of the open source community. For the OSS project she works on she wants it to be successful, popular, and it to be safe for use by the public and her company. For her company she wants to ensure that her work aligns with the goals of the company. She also wants to ensure that both her general open source work in the community as well as specific work on the project reflects well on the company.
- 
#### Personal
- Not to end up overloaded with work
- Seen as a good member of the open source community
#### Project
- Wants it to be successful, popular and it to be safe for use by the public and her company.
#### Company
- Wants to ensure that both her general open source work in the community as well as specific work on the project reflects well on the company.
- 
### Challenges: 
- It is difficult managing open source and company requirements especially if and when they conflict. Work planning is difficult since Mary deals both with internal company work but also deals with tickets coming from the community on her project. Mary needs to deal with unclear and fuzzy metrics compared to internal commercial work. This makes it more difficult for Mary to provide community adoption data, usage data, security data, etc. to both company stakeholders as well as other contributors and maintainers of the project. Mary is unable to use expensive commercial tools for performing common security tasks on the OSS projects like SCA, fuzzers, etc.
- It is difficult managing open source and company requirements, especially if and when they conflict.
- Work planning is difficult since Mary deals both with internal company work but also deals with tickets coming from the community on her projects.
- Needs to deal with unclear and fuzzy metrics compared to internal commercial work.  This makes it more difficult for Mary to provide community adoption data, usage data, security data, etc. to both company stakeholders as well as other contributors and  maintainers of the project.
- Unable to use expensive commercial tools for performing common security tasks on the OSS projects like SCA, fuzzers, etc.

### How the OpenSSF can help: 
- OpenSSF governance allows the open source project Mary maintains to fall under OpenSSF ownership if it meets OpenSSF scope and governance requirements and is voted on by the community. If it does fall under OpenSSF, it would be provided with support including security audit/review. Even if the project isn’t under OpenSSF, OpenSSF still can help through its portfolio of security projects under its governance. Mary can use projects like Scorecard to help get metrics on the security health of the project. If Mary’s project is considered critical to the safety of the community, it might fall under the work Alpha-Omega is doing. Mary can have the project follow the best practices, frameworks, and standards that come out of OpenSSF like SLSA, and S2C2F to better protect the project she maintains as well as help protect downstream consumers. Mary’s project also benefits from any projects in her software supply chain that themselves are utilizing OpenSSF tools and following best practices.

#### If project is OpenSSF project
- Security audit and review

#### If project isn’t OpenSSF project
- Scorecard to help get metrics on the security health of the project
- Allstar for ensuring adherence to security best practices
- If the project is critical to the community it might fall under work Alpha-Omega is doing to secure critical projects 
- The project can follow the various best practices, frameworks and standards coming out of OpenSSF like SLSA, and S2C2F.
- All the benefits of utilizing dependencies that also are helped by the OpenSSF

## Name: Ursula the Upstream Maintainer
- Full or part-time oss dev, not affiliated with a commercial organization (or work is not related to such).

### Role: 
- SRE for  tech company

### Background: 
- Ursula created an open source project on the weekend in order to learn a new programming language and other new tech. That project exploded in popularity and she continues to maintain it after hours and on the weekends along with support from some other volunteers she’s acquainted with. She also works at a tech company that allows her to work on the project but as it's unrelated to her day job requests that she only work on it after hours and with no implied or explicit company affiliation.

### Personal Goals:
- Not get fired for breaking company rules with respect to the open source project.
- To learn new tech and create something she thinks is cool. Her goal here isn’t to necessarily get adoption and therefore is not interested in achieving regulatory consistency that might be requested by {downstream consumers?}.
- To not get burnt out from working both a day job and doing after hours work on the project.

### Project Goals
- Create, update, and merge features that she wants to, along with input from the community
- Maybe one day turn it into a primary or side job
- Urusla has no intention of putting the project under an open source foundation while it’s just a side project

### Challenges:
- Requests come in both from individuals on their own behalf as well as persons representing large organizations demanding addition of features, assurances around security, etc. She does not get paid for her work on the project.
- Ursula is worried about upcoming legal requirements that might require her to either abandon the side project or have to figure out how to perform expensive, in both time and money, security and compliance tasks.
- Having time to devote to maintenance and updates is hard to find, especially large blocks of contiguous time.
- Interpreting the complicated jargon presented in issues opened against her projects especially those that might be requesting improvements of security and compliance.
- How the OpenSSF can help:
- OpenSSF provides a lot of automated tools that make it easier for Ursula to just integrate into her Github, and build that enforce project security.
- All the benefits of utilizing dependencies that also are helped by the OpenSSF
- Provide an easy on-ramp to the foundation that helps lessen the resources needed to implement this tooling and practices.
- OpenSSF needs to create things that are “easily consumable”: Merge requests / pull requests where practical, CONTRIBUTING guides, issue templates, “bite-sized” tasks (it’s easier to find time for many 15 minute tasks instead of an 8 hour block), “obviously right” solutions.

## Name: Diana the Weekend Warrior

### Role:
- working on open source software in their "spare time"
- maintains the project(s) by themselves
- started out as a way to learn new things for fun, has grown beyond that

 ### Background:
- I maintain a couple of small packages and contribute new medium size but impactful features to my underlying ecosystem. (Think a compiler optimisation for floats that takes a few months of work and extremely niche knowledge to get right) This is a really common and critical profile.
- Diana is in a loose network of other niche people doing the same in my ecosystem.
- Diana has challenges keeping their toolchain and CI systems up-to-date and running. C was not made for this kind of work, nor are most of the packaging ecosystem, and they have to fight with them all the time.
  
### Goals:
- keep the project going and as maintained as possible, given constraints of budget, time, and resources.
- 
### Challenges:
- Diana usually gets something like 2 hours per month to spend on FOSS. Sometimes up to 4h, sometimes less. 1 to 2h per month are dedicated to simply updating base dependencies. This is when it is just a few patches or minor versions. Sometimes up to 4 hours are taken for this. Sometimes a big major version in an important dependency happens and it takes us 10h to fix, over a quarter. This means that nearly all our time is spent handling dependency stuff. Basic stuff. Not security emergencies or anything like that. Releasing a new version that just is kept up to date basically.
- Diana does not have more time to give. Life is what it is; they have family, a job, friends, etc.
- Diana's tests for the project are in poor shape.  This is very well known.  They want to make them better, but per the above, there is no additional time to devote to this task.  Even something like fuzzing would be incredibly challenging to deal with the additional bugs that could be found, prioritized, and eventually (maybe) fixed.
- Diana has no additional time to read security-oriented material or the use. They know what need to be done.
- Most of Diana's time is spent fighting build and dependency management tools. This is a constant problem.  These tools often break in new and obscure ways. Oftentimes, features of the tool need to be disabled to even make things work and not break their builds.  There are proably ways around this, but again, see above, there is no additional time to troubleshoot, research, and adjust. Even the basic tools break too much and eat Diana's time.
- Reviewing and reacting to user reports is challenging.
- Sometimes, only updating minor versions breaks things for that dependency, which had an innocuous changelog?!?? Wait, they messed up their versioning. This was API breaking change, but they had no idea. I would have made the same mistake. It is not obvious. Aaaargh. Well i guess i will have to tell everyone to use the old version for the next 6 months while we spend our 6h per quarter all fixing it. I hope no emergency security patch comes through during that time.

### How the OpenSSF can help:
- Build and update tools and toolchains to be more aligned to the realities of Diana's work.

## Name: Stanislav the Student Maintainer
- Part-time dev working on passion or school project.  Low-to-no resources.



##### Name: Danika the Developer-Consumer

###### Role: 
- Software Engineer at Medium Sized Bank
  
###### Background: 
- Danika is a 9-5 software engineer at a bank. She does not do software development in the open source space though she does consume open source software as part of her job. She spends most of her day in an IDE writing software. Once a week she gets a report from security about SCA discovering vulnerabilities in her software.

###### Goals:
- Release features while hitting business deadlines and following bank compliance and policy requirements. These requirements involve vulnerability remediation deadlines, security control implementations, etc.
- Danika wants policy and compliance related feedback earlier in the SDLC loop. She would love to have information about using compliance (security, EOL, etc) in the tools she uses (IDEs, CLI tools, etc)

###### Challenges:
- She is just one developer in a large organization. She does not have the ability to drive meaningful change on her own. This means she is at the whims of the policies and process within the organization including security requirements even if those requirements might not be aligned with modern best practices.
- She does not have much if any security training outside basic quarterly training on how to identify common SQL injection attacks and similar.

###### How the OpenSSF can help:
- Interpreting the complicated internal jargon and requirements when creating issues in open source dependencies in order to request improvements of security and compliance.
- Creating forward thinking best practices and standards that can help Danika become more proactive in securing her software as opposed to reactive.
- This includes providing Danika with ammunition to help her push for change.
- OpenSSF through its work in helping define or collaborate on controls, standards, best practices, and regulations can drive industry and community change that will eventually be adopted in larger, often slower moving, enterprises.


