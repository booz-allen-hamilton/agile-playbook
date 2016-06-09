## Craftsmanship

Agile software engineering is still software engineering. Ron Jeffries tells us, "The software we build has to be robust enough to support the business need. It needs to be sufficiently free of defects to be usable and desirable. It needs to be well structured enough to allow us to sustain its development as long as required.

Robust, reliable, well designed. These are not things that we just automatically get by having a Product Owner and a Scrum Master. Much less are these things we get by having really good Portfolio Vision and an Agile Release Train... If we do not build it well, all our teamwork, communication, retrospectives, business focus and WIP limitation are for nothing" \[Jeffries 2015\].

> "If we do not build it well, all our teamwork, communication, retrospectives, business focus and WIP limitation are for nothing." - Ron Jeffries

Delivering great systems requires a dedication to the craft and an eye toward excellence. Technical agility and strength are necessary for teams to be truly agile. This section walks through practical ways to inject technical health into your solutions.

### Play: Build in quality

> Continuous attention to technical excellence and good design enhances agility.

We will delve into some ways to ensure quality is always considered in every aspect of software delivery. Security and quality cannot be thought of as bolt-on or follow-on functions after development is done. Building security and technical excellence into the solution as we go is a shared responsibility, and we need the team to continue to stretch itself to achieve better results over time. The team will do this by using agreed-upon practices, talking together, regularly inspecting, and automating their work.

> **Anti-Pattern  - Poor technical practice** >  Agile does not dictate technical practices, but often it highlights issues that have existed.  Increasing the pace of deployments or automation shows weaknesses in the technical practices through a faster learning cycle, the goal is to decrease time dedicated to defect correction or manual processes that can slow down a team.

#### Practice: Technical Definition of Done
In addition to the Product Owner accepting user stories as complete, the team must also determine what practices they will follow to determine when the user story is of sufficient quality to review with the Product Owner.  This definition of done must be explicitly discussed and followed by all team members.  The definition often includes the practices within this play.  An example may look like this:

1. Code complies with the standards agreed upon through manual or automated static code inspection
1. Unit test has been written and passed
1. Code has been reviewed by a peer
1. Code has been checked in to a repo
1. Code has passed automated or manual security and/or compliance inspection
1. Code has been successfully integrated into a build 
1. User story has been successfully deployed to a test environment 
1. User story has passed functional testing

> **Anti-Pattern - No Definition of Done** > When a team has not established and agreed to a definition of done there can be confusion. Each team member has a differing opinion of what "done" means. Whether it's applied to stories, features, epics, sprint, release, ready for production, etc. the definition of done should be established by the team prior to the work being accomplished. This is usually during team chartering but can be established at anytime prior to planning the work. This level setting across the team means they can hold one another accountable when it comes time to deliver. This also prevents the lingering story that never seems to be done. 
 

#### Practice: Adopt a coding standard
Forming a **coding standard** is an essential task for any agile team. Creating agreed-upon documentation that defines the style in which code will be written and any practices to be followed or deemed unacceptable prevents the occurrence of potential problems. The team’s coding standards also likely will include topics such as how errors are handled and how code is structured (directory convention, etc.). The intent is to ensure the delivery team develops code uniformly, which aids future code updates and developer comprehension and eases code review. Coding best practices fall into two groups: independent best practices (e.g., variable naming conventions) and dependent best practices (e.g., how to use aspect-oriented programming principles).

The team and its senior developers should define the initial coding best practices the team will use during software development activities. These practices should be presented to the team and discussed in detail to ensure complete understanding of how to execute acceptable coding practices, as well as the implications of not doing so. During retrospectives, these practices should be considered and modified as needed to reflect possible improvements for the team.

> **Anti-Pattern - No documentation** > Agile is not an excuse to toss out all of your documentation!  The Manifesto simply states "Working software over _comprehensive documentation"_. But, we do emphasize looking at your documentation and understanding its value proposition, just as we do for features we build.  Who is asking for it?  Why are they asking for it?  What will it be used for?  If you are on a team that is not documenting anything, it is worth investigating.


#### Practice: Paired Work
Pairing with a colleague benefits the team through early identification of potential issues, shortened review cycles, and enhanced commitment to the quality of the product, in addition to being a learning opportunity for both parties. It should be employed when creating any artifact for the project, from code through documentation. 

#### Practice: Code reviews
There are two primary benefits of **code reviews**. First, any bug found during review is cheaper to fix then (by orders of magnitude) than if it is found later in the process. Second, a team that is practiced in inspecting the code tends to be able to embrace the agile principle of collective code ownership. All of the code (and any bugs identified) is the responsibility of the team, rather than a specific individual. This mindset results in a tighter, higher quality product.

Agile teams use code reviews to identify and fix bugs and weaknesses that may have been overlooked. Code reviews also enable senior developers to mentor junior developers on how to write better quality code.

Code reviews are performed for all code changes and should be included in the team’s software development workflow. Generally, code is not included in the next build or made available to the test team unless the team has held an review on that code. Typically, the following elements will be included in the team’s code review practice:

* Review changed code.
* Verify functionality.
* Review results of security and code quality scans.
* Review test case results, including any automated unit or regression tests.

Teams should create a brief training for new developers to introduce them to how reviews work on their team.

For code reviews:

Do...

*    Look for code style issues
*    Look for obvious coding mistakes
*    Ask questions/pose alternatives if code appears complex
*    Look for code areas that seem fragile
*    Provide constructive feedback, contributing to a solution if possible
*    Look for concise and clear comments to explain unusual cases, techniques, and anything that feels non-obvious
*    Be respectful in your comments—picking apart someone else’s code can make the author feel vulnerable
*    Ensure someone has the job to shepherd the review through timely completion
*    Ensure team members have had a chance to review code before considering the review Done
*    Link the code review artifacts with how you track the original work request (ticket, requirement, etc.).

Don't...

*    Close out a review someone is actively working on
*    Try to obtain a 100% complete understanding of all the code
*    Examine every possible input case; this also takes way too much time
*    Expect overly verbose comments.

Collaborative code reviewing tools, such as Atlassian’s Crucible, provide the ability for inline comments for code with informative feedback. Additionally, look for ways to automate code quality basic review using review tools such as Atlassian Clover or Code Climate.

#### Practice – Source code analysis
**Source code analysis** is empirically proven to be one of the most effective pre-test defect-prevention techniques, increasing quality and reducing downstream rework. We required more advanced methods to address defects, vulnerabilities, and sub-standard coding practices to ensure the highest levels of structural quality, maintainability, and security before application deployment. Project teams needed an automated and repeatable way to measure and improve the application software quality of multi-platform, multi-language, and multi-sourced applications. Implementing source code analysis includes:

* Planning for and incorporating code scanning as part of the continuous integration activities to have a real-time characterization of application health at the code level with tools such as SonarQube
* Performing structural quality scan on the code with tools such as CAST; using scan results as a way to direct development efforts due to specific vulnerabilities or business priorities.

> **Anti-Pattern Not enough attention to quality** > Agile is sometimes only seen as the ability to deliver faster, and that becomes the only focus.  By building in multiple layers of checks and testing, less time correcting defects is needed in the long run.  Build quality check practices into your processes, and look for opportunities to automate them.  This will ensure fewer defects and less time fixing those defects.  The cost of a defect found early in the lifecyle is signifigantly cheaper to fix than those in production.


#### Practice: Secure coding
**Secure coding** is a practice to prevent known vulnerabilities and keep the code secure by refactoring as new vulnerabilities are identified, or as the environment (operating systems, browsers, web specifications, etc.) changes. Implementing this practice includes:

* Defining secure coding practices at the start of the project
* Reviewing practices during the code review for the checked-in file
* Using free open-source software that checks against defined best practices (general coding practices and custom practices that the team defines in the tool); see the Tools section of this document for more information on code review and scanning tools
* Integrating automated code reviews into code check-in and continuous integration to gain the best results with minimal manual effort
* Scanning applications for vulnerabilities on the server. Three types of scans would benefit the team:
  * Scan the server for container-based vulnerabilities. The Retina network security scanner is one of the best tools to use for this purpose; another tool for the same purpose is the Nessus Vulnerability scanner
  * Perform static analysis on the code with tools such as IBM Appscan or HP Fortify
  * Perform automated penetration testing using tools such as Hailstorm
* Documenting the actions to be taken for each type of scan.

Secure coding best practices incorporate the Open Web Application Security Project (OWASP) Enterprise Security Application Programming Interface (ESAPI) to simplify and standardize the implementation of security functions in the environment, unless environmental factors prohibit deployment. OWASP ESAPI toolkits help software developers guard against security-related design and implementation flaws by ensuring simple, strong security controls are available to every developer. An integrity check of software products is included to facilitate organizational verification of software integrity after delivery.

#### Practice: Address security through the entire stack

From physical location to client facing application, teams must be versed in the skill-sets needed to ensure applications are secure.  All talent from development to security professionals should be security-minded: trained in software development practices that are secure throughout.  This includes not only awareness of threats and attack vectors in the layer of application being built but also the surrounding layers; layers belonging to partners, shared libraries, and so-on.  Further, as security concerns span the entire application, an approach that only addresses one layer in the stack is especially at risk for breaches in any of the other layers.  Defense-in-depth is an architectural security pattern, well suited for modern applications, which employs a multi-layered approach to security. As a team, practice continual learning and diligence in understanding your technology stack and its security posture.

As a starting point, regularly consider these elements -

1. Are security tools used to check software vulnerabilities, and we decide on an action for each vulnerability?
1. Are security scans included as a part of each automated build, and that security posture is radiated to the team and stakeholders?
1. Have compliance requirements, such as NIST, RMF, 800-53 for example, been addressed as technical stories?
1. Does your security strategy also address containers, network, firewalls and operating system for vulnerabilities?  As an example, Netflix’s Security Monkey is a tool that checks the security configuration of your cloud implementation on AWS.
1. Have functional security test scripts been developed and executed to verify security features, such as authorization, authentication, field level validation, PII compliance?
1. Does the configuration of security components such as the perimeter firewall, Intrusion Detection / Prevention System (IDS/IPS) follow a similar model in terms of provisioning and configuration as application servers? Use Infrastructure-as-Code artifacts, to describe these configurations, to ensure that the ability to consistently and repeatedly configure components, prevent system administration drift, and support audits and traceability of changes.
1. Is advanced network monitoring in place to actively find vulnerabilities or active attacks?
1. Is security talent embedded within teams and each team member from developer to security professional are security-minded?   Remember, security is a shared concern.
1. Is the process of defining, implementing and monitoring security, from beginning to end, an iterative cycle throughout the life of the software?  This is a proven strategy as illustrated by The US Postal, Secure Digital Solutions, Electronic Postmark Identify Proofing project.
1. Are software security fundamentals implemented, such as OWASP’s Top 10, as well as project-specific security concerns, such as HIPAA or PII compliance?


#### Practice: Refactor your solutions
Code refactoring is a technique for restructuring an existing body of code—altering its internal structure without changing its external behavior. We refactor to improve the nonfunctional attributes of the software. Advantages include improved code readability and reduced complexity to support maintenance. There are two other benefits to refactoring:

* **Maintainability.** It is easier to fix bugs/defects when the source code has been written so that it is easy to understand and grasp. This might be achieved by reducing large routines into a set of individually concise, well-named, single-purpose methods. It might also be achieved by moving a method to a more appropriate class or by removing misleading comments.
* **Extensibility.** It is easier to extend the capabilities of an application if it uses recognizable design patterns and provides some flexibility where it may not have existed previously.

#### Practice: Invest in unit testing
Unit tests are a foundational software engineering practice for development teams. This practice refers to developers writing small tests that test individual components in the system, typically with code that’s automatically run during builds. Designing unit testing is a challenging task for the development team. The unit test infrastructure and architecture need to be designed during Sprint 0 of the project. The unit tests could cover all layers of the application or target only certain layers.

Unit tests should be included in the definition of done for any work item, and developers should discuss plausible test strategies when the work is planned. When a developer makes the code ready for the sprint’s releasable software, this indicates that the unit tests are also ready. 



### Play: Build in quality ... and check again
Testing incremental functionalities of the product developed by the agile team involves reviewing the user stories to ensure they meet the definition of done, are considered complete, and have passed the acceptance testing criteria. Preparing for testing activities includes any artifacts required to successfully execute testing, such as the scripts, code, and data. The objective of any testing activity is to determine whether the incremental product developed satisfies the intended requirements and also proves to be a testable component. Along with functional and regression testing activities, automated testing and acceptance testing are also performed.

> **Anti-Pattern No testing** > If you have a project that seems straight forward or you are very familiar with the technology, it may seem like testing is just going to slow you down.  A key tenet of the Manifesto is "Working software."  Whatever we deliver has to work, and we have to know that it works.  Testing may just confirm what you already know, but is part of technical excellence and a foundation of quality.

#### Practice:  Use test-driven development (TDD)
TDD is a software development practice that increases code quality by ensuring high unit test coverage. Unit test coverage has been proven to increase overall code quality by providing the first level of test on which later testing continues to check additional quality factors. When using TDD, developers write a unit test first, then produce only enough code to pass that test, then refactor the code to elegantly integrate into the existing codebase. When diligently followed, this practice builds the foundation for a robust, tested body of code.

TDD is performed whenever code is written. It is **not a testing methodology**; it is a software development technique. The objective is 100% coverage for all software with automation.

The system’s correct behavior is well-defined in the body of tests that developers can confidently make changes and deploy. These tests augment any code documentation by demonstrating the functionality, enabling developers unfamiliar with the code to quickly become comfortable with the intended code behavior.

#### Practice:  Functional testing
The team performs *functional testing* to ensure the functional behavior of the product (or system) corresponds to its specifications; this involves testing one component at a time. Unit testing focuses on testing the smallest individual units or components of the build, application modification, or system to verify that each component is built to design specifications. Functional testing is performed after the component has been unit tested to verify functionality against the requirements and specifications and before system and integration testing.

#### Practice:  Regression testing
The team performs *regression testing* to isolate and resolve any errors or defects introduced during modifications based on change requests. This testing verifies that the component still meets its specified requirements and no adverse effects have been identified as a result of implemented changes. Regression testing focuses on executing test scripts and/or scenarios in functional and nonfunctional areas of a system after changes have been made, ensuring the product or system still meets its specified requirements and will not fail when deployed to the operational environment or adversely affect code currently in production. The agile team should conduct a degree of regression testing at the end of each level of testing to ensure any defects corrected during each testing segment have not caused additional defects. Over time, we encourage all of our teams to strive for automated regression testing to the greatest degree possible.

> **Anti-Pattern Security and QA happens at the end** > The security and QA groups aren't on the team, so you exclude them from the sprint plans.  Changing your approach to committing work can sometimes mean bringing in groups who were previously a different department.  Its easy to forget about the QA or security people if they are not actively part of your teams.  Leaving security and QA until the end equates to phases in traditional waterfall. If something is discovered in security or QA the story must go back to the team for rework. At this point the team has already moved onto new stories and must stop to accomplish the rework. The discovery may affect more than one story which results in extra effort to fix the problems. If security and QA can be included throughout the lifecycle, problems can be uncovered early before requiring much rework. This also promotes collaboration and shared committment to security and quality as one team delivering solutions.

#### Practice:  Automated testing
*Automated testing* must be considered part of the software development cycle. The tests themselves are an integral part of software development because they help minimize time spent debugging and help the team identify and resolve issues before users do. Prior to committing code, the code should be thoroughly subjected to automated test, and those tests should be committed with the code. This helps team members ensure their work is compatible with the code being committed. The entire automated test suite should be run against all code changes before that code is committed to ensure there are no conflicts with other areas of the project. When a bug is found in the system, the developer committed to fixing the bug should perform the following steps:

1.	Write a unit test that expects the specific failing behavior not to occur.
2.	Run the test, which should fail because the bug will still be in the code.
3.	Fix the bug.
4.	Run the unit test to ensure the test now passes.

This practice ensures the bug can never be reintroduced into the system without being caught by the automated test suite.

#### Practice:  User feedback and acceptance testing
Successful agile projects regularly put new software in front of the users for immediate feedback. This does not require a deployment to a production server but does require a demonstration or test server to which users have access and can try out new features still in development. Making this environment available increases communication between the users and the agile team. If features are found to be off track, the developers can start over, with only the loss of a sprint’s worth of work versus 6 months or more if discovered later. User testing has the added benefit of showing users that while you may not have had a deployment recently, you are making progress on the highest priority request.

### Play: Automate as much as you can

#### Practice:  Use continuous integration
Continuous integration is a foundational agile technical practice. It requires each team member to integrate their latest work with the trunk frequently—at least daily—and to have each integration verified by an automated build (with automated testing included). Continuous integration increases the quality of the software by reducing the defect escape rate and decreases maintenance and sustainment costs. Developers working from a local copy for days at a time is a bad practice and contributes to risky, complicated merges; continuous integration mitigates this risk.

Continuous integration means that unit tests are executed every time automated test builds are generated from the code repository. If one of the unit tests should fail during execution, the continuous integration mechanism notifies the project team every time it tries to execute the test, until the problem is resolved.

Continuous integration tools can be set up to notify the development team of any failed build. These enable the team to resolve small integration issues early, before they become large or multiple issues just prior to a release or deployment.

When combined with automated testing, code quality inspection tools, and vulnerability scanning tools, continuous integration becomes an even more powerful tool for the agile team. Automated unit tests identify problems early and prevent integration defects from piling up—reducing risk to release candidates and product deliveries. Automated code quality inspection tools and vulnerability scanning tools can identify poor coding practices, code violations, and security violations without the need for additional developer code review. Continuous integration increases code quality and reduces bugs in the deployed software.

Teams that practice continuous integration tend to be able to complete a build easily and have a lower cost of change than teams that have to manually exercise their build process.

Guidelines for successful continuous integration include:

* Providing the ability for a “one-click-build”
* Executing automated builds at every commit or at least once daily
* Achieving 60% unit test code coverage as a target, with anything above 70% considered exceptional
* Providing automated notification to the entire development team when a build or unit test fails.

#### Practice:  Continuous delivery and continuous deployment
When a team has continuous integration working well, it can consider the more mature practices of continuous delivery and continuous deployment.

Continuous integration gets us as far as having a server somewhere that builds the software and runs the automated tests, but it doesn’t get it off that build server. Continuous delivery is that next step: ensuring each change to the software is packaged up and releasable, and we can push it to production with click. This means we must have automated and smoothed all the mechanical steps of the release and deployment process, which often slows down teams. In a continuous delivery environment, releases become boring.

Continuous deployment goes one more level. Each change is pushed to production automatically. You must be practicing continuous delivery before you can consider continuous deployment. To make this leap, all the qualitative and judgment aspects of releases that might have been performed by humans before are now automated. Do we really trust the automated QA? Have we covered the edge cases? Does this release degrade performance anywhere? Is the timing right for the business? When the software can automatically stop releases that should not go out but lets the others pass, we’ve reached continuous deployment.

#### Practice:  Continuous monitoring
To have success with continuous delivery and continuous deployment, you must have the backbone of continuous monitoring in place. Without the ability to know how the application is performing, the processes in place no longer stand.

Continuous monitoring is constant validation that the application is functioning and performing as expected. Through the creation of monitoring tools, teams are able to remain confident that the applications are performing and functioning at their optimal levels. This means that we must know there is a failure before one occurs and build feedback mechanisms to gather information from the system. 

When gathering information, it is important to understand: 
* How and why is early detection of defects important to your project? 
* What is the system availability requirement and what is the plan to achieve it? 
* What is the labor cost of your operations? 
* How many systems engineers, systems administrators, and database administrators do you have monitoring the production environments, and how do they react when there is an issue? (DevOps Playbook) 

When keeping these questions in mind with continuous monitoring, teams are able to find issues and defects early and automatically, which in turn increases overall confidence and reliability in the application.

#### Practice: DevOps
DevOps applies a software mindset to how systems get deployed and maintaned.  Similar to agile itself, DevOps is more of a mindset, with principles than it is any particular set of practices. A common way to describe it is with the acronym CAMS:  Culture, Automation, Monitoring and Sharing.  These principles dovetail with the overall agile principles while expanding the scope to include anyone involved in releasing, delivering, and maintaining software and its infrastructure. The aims of a DevOps implentation are to: 

1. Reduce risk
1. Increase velocity, and 
1. Improve quality.

Although it addresses a fundamental need, DevOps is not a simple solution to master. By integrating software developers, quality control, security engineers and IT operations, DevOps can provide a platform for new software or program fixes to be deployed into production as quickly as it is coded and tested. That’s the idea, anyway – but it is easier said than done. To excel at DevOps, teams and organizations must do the following:

* Transform their cultures;  
* Automate legacy processes; 
* Design contracts to enable integration of operations and development; 
* Collaborate and then collaborate some more; 
* Honestly assess performance; and 
* Reinvent software delivery strategies based on lessons learned and project requirements. 

Specifics on implementing DevOps can be found in the Booz Allen DevOps Playbook.

#### Practice:  Seek an agile architecture
An architecture that supports agile projects must support the current effort and any future complexities. Loosely coupled service-oriented architectures are often used to leave room for future changes.  Advancements in technology such as microservices and containerization affect the nature of the architecture and change the need to a virtualized infrastructure.  Many projects do not have the luxury of starting new and need the legacy infrastructure and construct integrated. When these complexities arise, tailored solutions that take into account latency or potential performance issues must be developed with the end-user experience in mind. Architecture, just like any other part of the development is work that must be planned, executed, and accounted. The more complex the solution, the more planning is needed for infrastructure as well as application architecture.  Using an architectural roadmap to plot out future needs will provide a type of scaffolding that will then be completed with a detailed design that builds out just enough infrastructure or detail needed to complete features.  Depending on the size of architecture being built, one or several Architectural Epics are executed through technical spikes within the sprints.  The level of documentation and diagrams needed will be informed by the agile principles in mind during development and implementation.
