> Continuous attention to technical excellence and good design enhances agility.

> Simplicity--the art of maximizing the amount of work not done--is essential.

> The best architectures, requirements, and designs emerge from self-organizing teams.

### Craftsmanship in development teams
Craftsmanship is expressed by an agile team taking pride in ownership through simultaneous thoughtful design and an emphasis on quality code to create a sustainable product.  An agile team employs multiple methods to build in quality and robustness to the product, creating technical agility. The team strives for a product that has been continuously reviewed, continuously tested, and which has been refined and simplified as much as possible. The practices and process that a team uses are owned by the team itself. How a team incorporates craftsmanship to their solutions should be a common discussion among the team, and an area that the team strives to regularly improve.

### Adopt a Coding Standard
Forming a **coding standard** is an essential task for any agile team. Creating agreed-upon documentation that defines the style in which code will be written and any practices to be followed or deemed unacceptable, prevent the occurrence of potential problems. The team’s coding standards also likely will include topics such as how errors are handled and how code is structured (directory convention, etc.). The intent is to assure the Delivery Team develops code uniformly, which aids future code updates and developer comprehension, and eases code review. Coding best practices fall into two groups, independent best practices (e.g., variable naming conventions) and dependent best practices (e.g., how to use aspect-oriented programming principles).

During Sprint 0, the agile team and its senior developers should define the coding best practices the team will use during software development activities. These practices should be presented to the team and discussed in detail to assure complete understanding of how to execute acceptable coding practices, and the implications of not doing so. During Retrospectives, these practices should be considered and modified as needed, to reflect possible improvements for the team.

### Peer Review
Peer review benefits the team increasing through quality early identification of potential issues, as well engaging team mates in overall commitment to the quality of the product, in addition to being a learning opportunity for both parties.  It should be employed when creating any artifact for the project from code through documentation.  Specifically addressing code peer review, a reviewer should be named and given a due date for the review.  The reviewers should examine the code for coding standards, cohesiveness, opportunities for efficiencies, and potential integration issues.  Ideally the review happens with the developers paired, discussing and making changes together.  Peer review helps build relationships that encourage individuals to ask questions and provide assistance to team mates, and reinforces the collective ownership of the product.

### Do Code Reviews
There are two primary benefits of **code reviews**. First, any bug found during inspection is cheaper to fix then (by orders of magnitude) than if it is found later in the process. Second, a team that is practiced in inspecting the code tends to be able to embrace the agile principle of collective code ownership. All of the code (and any bugs identified) are the responsibility of the team, rather than a specific individual. This mindset results in a tighter, higher-quality product.

Collaborative code reviewing tools, such as Atlassian’s Crucible, which is a part of our SmartSuite environment, provide the ability for inline comments for code with informative feedback. agile teams use code reviews to identify and fix bugs and weaknesses that may have been overlooked. Code reviews also enable senior developers to mentor junior developers on how to write better quality code.

Code reviews are performed for all code changes and should be included in the team’s software development workflow. When developers complete coding for a task, the status of the task becomes “code review,” and the Technical Lead is notified by automated email. Code is not included in the next build or made available to the test team unless the Lead Developer reviews the code with the developer present. If rejected, the task returns to the developer. If approved, the task status changes in the scope tracker to include the code in the next test build. The team should decide which of the following elements will be included in the team’s code review practice:

* Changed code
* Results of security and code quality scans
* Test case for the capability
* Functionality

### Strive for Secure Coding
**Secure coding** is using best practices to prevent known vulnerabilities and keeping the code secure by refactoring as new vulnerabilities are identified, or as the environment (i.e., operating systems, browsers, web specifications, etc.) changes. Implementing this practice includes:
* Defining secure coding best practices at the start of the project.
* Reviewing practices during the code review for the checked-in file.
* Using free open-source software that checks against defined best practices to review the code against general coding practices and against custom practices that the team would define within the tool. See the Tools section of this document for more information on code review and scanning tools.
* Integrating automated code reviews into code check-in and continuous integration to gain the best results with minimal manual effort.
* Scanning applications for vulnerabilities on the server. Three types of scans would benefit the team:
*  Scan the server for container-based vulnerabilities. The Retina network security scanner is one of the best tools to use for this purpose. Another tool for the same purpose is the Nessus Vulnerability scanner.
*  Perform static analysis on the code with tools such as IBM Appscan or HP Fortify.
*  Perform automated penetration testing using tools such as Hailstorm.
*  Documenting the actions to be taken for each type of scan.

Secure-coding best practices incorporate the Open Web Application Security Project (OWASP) Enterprise Security Application Programming Interface (ESAPI) to simplify and standardize the implementation of security functions in the environment, unless environmental factors prohibit deployment. OWASP ESAPI Toolkits help software developers guard against security-related design and implementation flaws by ensuring simple, strong security controls are available to every developer. An integrity check of software products is included to facilitate organizational verification of software integrity after delivery.

### Refactor your solutions
Code refactoring is a technique for restructuring an existing body of code, altering its internal structure without changing its external behavior. We refactor to improve the nonfunctional attributes of the software. Advantages include improved code readability and reduced complexity to support maintenance. There are two general benefits:
* **Maintainability** > It is easier to fix bugs/defects when the source code has been written so that it is easy to understand and grasp. This might be achieved by reducing large routines into a set of individually concise, well-named, single-purpose methods. It might also be achieved by moving a method to a more appropriate class or by removing misleading comments.
* **Extensibility** > It is easier to extend the capabilities of an application if it uses recognizable design patterns and provides some flexibility where this may not have existed previously.

### Invest in Unit Testing
Unit tests are a foundational software engineering practice for development teams. It refers to developers writing small tests that test individual components in the system, typically with code that's automatically run during builds. Designing unit testing is a challenging task for the development team. The unit test infrastructure and architecture need to be designed during Sprint 0 of the project. The unit tests could cover all layers of the application or target only certain layers.

Unit tests should be included in the definition of “Done” for any work item, and developers should discuss plausible test strategies when the work is planned. When a developer makes the code ready for the Sprint’s releasable software, this indicates that the unit tests scoped for the code are also ready and included in continuous integration. Continuous integration means that unit tests are executed every time automated test builds are generated from the code repository. If one of the unit tests should fail during execution, the continuous integration mechanism notifies the project team every time it tries to execute the test, until the problem is resolved.

### Use Continuous Integration
Continuous integration is a foundational agile technical practice. It requires each team member to integrate their latest work with the trunk frequently -- at least daily -- and to have each integration verified by an automated build (with automated testing included). Continuous integration increases the quality of the software by reducing the defect escape rate, and decreases maintenance and sustainment costs. Developers working from a local copy for days at a time is a bad practice and contributes to risky, complicated merges; continuous integration mitigates this risk.

Continuous integration tools can be set up to notify the development team of any failed build. This enables the team to resolve immediately small integration issues early, before they become large or multiple issues just prior to a release/deployment.

When complemented with **automated unit testing**, code quality inspection tools, and vulnerability scanning tools, continuous integration becomes an even more powerful tool for the agile team. Automated unit tests identify problems early and prevent integration defects from piling up, reducing risk to release candidates and product deliveries. Automated code quality inspection tools and vulnerability scanning tools can identify poor coding practices, code violations, and security violations, without the need for additional developer code review. Continuous integration increases code quality and reduces bugs in the deployed software.

Teams that practice continuous integration tend to be able to complete a build easily and have a lower cost-of-change than teams who have to manually exercise their build process. 

Guidelines for successful continuous integration include:

* Providing the ability for a “one-click-build”
* Executing automated builds at every commit or at least once daily
* Achieving 60-percent unit test code coverage as a target, with anything above 70 percent considered exceptional
* Provide automated notification to the entire development team when a build or unit test fails.

### Continuous Delivery and Continuous Deployment
When a team has continuous integration working well, they can consider the more mature practices of Continuous Delivery and Continuous Deployment. 

Continuous integration gets us as far as having a server somewhere that builds the software and runs the automated tests, but it doesn't get it off that build server. Continuous Delivery is that next step -- ensuring each change to the software is packaged up and releasable, and we can push it to production with click. This means we must have automated and smoothed all the mechanical steps of the release and deployment process, which often slows down teams. In a Continuous Delivery environment, releases become boring. 

Continuous Deployment goes one more level -- each change is pushed to Production automatically. You must be practicing Continuous Delivery before you can consider Continuous Deployment. To make this leap, we must now automate all those qualitative and judgment aspects of releases that might have been performed by humans before: Do we really trust the automated QA? Have we covered the edge cases? Does this release degrade performance anywhere? Is the timing right for the business? When the software can automatically stop releases that should not go out, but let the others pass, we've reached Continuous Deployment.   

### DevOps
DevOps is the concept of Development teams and Operations working together to improve the overall system from inception to Operations and Maintenance.  Just as agile is a Mindset, DevOp is also a mindset with principles.  The most commonly applied concepts are CAMS:  Culture, Automation, Monitoring and Sharing.  These principles dovetail with the overall agile principles while expanding the concepts through Operations groups.

Culture guides both Development teams in considering operations and maintenance needs in development design and execution.  Automation encourages automation of testing, integration, code deployment, as well as automated monitoring.  Monitoring includes environment, application monitoring, security, as well creating a dashboard to summarize all aspects of the system from development through production performance.  Sharing also encourages breaking down stovepipes to encourage groups to share their observations and knowledge to prevent or quickly reduce technical issues.

Specifics on implementing a DevOps system can be found in the Booz Allen DevOps playbook.

### Continuous Monitoring
In order to have success with Continuous Delivery and Continuous Deployment, you must have the backbone of Continuous Monitoring in place.  Without the ability to know how the application is performing, the processes in place no longer stand.

Continuous Monitoring is constant validation that the application is functioning and performing as expected.  Through the creation of monitoring tools, teams are able to remain confident that the applications are performing and functioning at their optimal levels.  

This means that we must know there is a failure before one occurs, and build feedback mechanisms to gather information from the system.  When gathering information it is important to understand: How and why is early detection of defects important to your project? What is the system availability requirement and what is the plan to achieve that? What is the labor cost of your operations? How many systems engineers, systems administrators, and database administrators do you have monitoring the production environments and how do they react when there is an issue? (DevOps Playbook)  When keeping these questions in mind with Continuous Monitoring, teams are able to find issues and defects early and automatically, which in turn increases the overall confidence and reliability in the application.


### Seek an agile architecture
//TODO

### Use Test-Driven Development
TDD is a software development practice that increases code quality by ensuring high unit test coverage.  Unit test coverage has been proven to increase overall code quaility by providing the first level of test on which later testing continues to check additional quality factors.  When using TDD,  developers write a unit test first, then produce only enough code to pass that test, then refactor the code to elegantly integrate into the existing codebase. When diligently followed, this practice builds the foundation for a robust, tested body of code.

TDD is performed whenever code is written. It is **not a testing methodology**; it is a software development technique. The objective is 100-percent coverage for all software with automation. The automated TDD test suite is generally executed with each build, but at least once a day as part of the continuous integration to check the state of the software. Automatic TDD tests executed during a automated integration builds serve to immediately identify new defects, or integration issues.

The system's correct behavior is well defined in the body of tests that developers can confidently make changes and deploy.  These tests augment any code documentation by demonstrating the funcationality enabling developers unfmailiar with the code to quickly become zunderstand with the intended code behavior. 

## Testing
Testing incremental functionalities of the product developed by the agile team involves reviewing the User Stories to ensure they meet the definition of “Done,” are considered complete, and have passed the acceptance testing criteria. Preparing for testing activities includes any artifacts required to successfully execute testing, such as the scripts, code, data, etc. The objective of any testing activity is to determine whether the incremental product developed satisfies the intended requirements and also proves to be a testable component. Along with Functional and Regression Testing activities, Automated Testing, and Acceptance Testing are also performed.

###Functional Testing
The team performs **functional testing** to ensure that the functional behavior of the product (or system) corresponds to its specifications, which involves testing one component at a time. Unit Testing focuses on testing the smallest individual units or components of the build, application modification, or system, to verify that each component is built to design specifications. Functional testing is performed after the component has been unit tested to verify functionality against the requirements and specifications, before system and integration testing.

###Regression Testing
The team performs **regression testing** to isolate and resolve any errors or defects introduced during modifications based on change requests. This testing verifies that the component still meets its specified requirements and no adverse effects have been identified as a result of implemented changes. Regression testing focuses on executing test scripts and/or scenarios in functional and non-functional areas of a system after changes have been made; ensuring the product/system still meets its specified requirements, and will not fail when deployed to the operational environment or adversely affect code that is currently in production. The agile team should conduct a degree of regression testing at the end of each level of testing to ensure that any defects corrected during each testing segment have not caused additional defects.

###Automated Testing
**Automated testing** must be considered part of the software development cycle. The tests themselves are an integral part of software development because they help minimize time spent debugging and help the team identify and resolve issues before users do. Prior to committing code, the code should be thoroughly subjected to automated test, and those tests should be committed with the code. This helps team members ensure their work is compatible with the code being committed. The entire automated test suite should be run against all code changes before that code is committed to ensure that there are no conflicts with other areas of the project.
When a bug is found in the system, the developer committed to fixing the bug should follow the following steps:

1. Write a unit test that expects the specific failing behavior not to occur
2. Run the test, which should fail because the bug will still be in the code
3. Fix the bug
4. Run the unit test to ensure the test now passes.

This practice ensures the bug can never be reintroduced into the system without being caught by the automated test suite.

###User Feedback or Acceptance Test
Successful agile projects regularly put new software in front of the users for immediate feedback. This does not require a deployment to a production server but does require a demonstration or test server to which users have access and can use to try out new features still in development. Making this environment available increases communication between the users and the agile team. If features are found to be off track, the developers can start over, with only the loss of a Sprint’s worth of work versus 6 months or more if discovered later. This has the added benefit of showing users that while you may not have had a deployment recently, you are making progress on the highest priority request.

