> Continuous attention to technical excellence and good design enhances agility.

> Simplicity--the art of maximizing the amount of work not done--is essential.

> The best architectures, requirements, and designs emerge from self-organizing teams.


# Probably SPARC

- Continuous Integration, Deployment, Delivery
- DevOps
- Continuous Monitoring
- Agile Architecture
- TDD


### Development
An agile team employs multiple methods to build in quality and robustness to the product, creating technical agility. These methods include secure coding standards and best practices that the team must follow, using code refactoring, applying version control methods, and using continuous integration to merge developed code. Test-Driven Development (TDD) is a software development practice that aggressively increases code quality and testability, providing another avenue for Agile teams to subject their code to strenuous code reviews and refactoring techniques.

###Coding Standard—Best Practices
Forming a **coding standard** is an essential task for any Agile Team. Creating agreed-upon documentation that defines the style in which code will be written and any practices to be followed or deemed unacceptable, prevent the occurrence of potential problems. The team’s coding standards also likely will include topics such as how errors are handled and how code is structured (directory convention, etc.). The intent is to assure the Delivery Team develops code uniformly, which aids future code updates and developer comprehension, and eases code review. Coding best practices fall into two groups, independent best practices (e.g., variable naming conventions) and dependent best practices (e.g., how to use aspect-oriented programming principles).

During Sprint 0, the Agile Team and its senior developers should define the coding best practices the team will use during software development activities for each Sprint. These practices should be presented to the team and discussed in detail to assure complete understanding of how to execute acceptable coding practices, and the implications of not doing so. During the Sprint Retrospective, these best practices should be reviewed, modified as needed, and improved on to enhance the performance in subsequent Sprints.

###Secure Coding—Best Practices
**Secure coding** is using best practices to prevent known vulnerabilities and keeping the code secure by refactoring as new vulnerabilities are identified, or as the environment (i.e., operating systems, browsers, web specifications, etc.) changes. Implementing this practice includes:
* Defining secure coding best practices at the start of the project.
* Reviewing practices during the code review for the checked-in file.
* Using free open-source software that checks against defined best practices to review the code against general coding practices and against custom practices that the team would define within the tool. Please see **toolsrepository.bah.com** or **Section 6** of this document for more information on code review tools.
* Integrating automated code reviews into code check-in and continuous integration to gain the best results with minimal manual effort.
* Scanning applications for vulnerabilities on the server. Three types of scans would benefit the team:

*  Scan the server for container-based vulnerabilities. The Retina network security scanner is one of the best tools to use for this purpose. Another tool for the same purpose is the Nessus Vulnerability scanner.
*  Perform static analysis on the code with tools such as IBM Appscan or HP Fortify.
*  Perform automated penetration testing using tools such as Hailstorm.
*  Documenting the actions to be taken for each type of scan.

Secure-coding best practices incorporate the Open Web Application Security Project (OWASP) Enterprise Security Application Programming Interface (ESAPI) to simplify and standardize the implementation of security functions in the environment, unless environmental factors prohibit deployment. OWASP ESAPI Toolkits help software developers guard against security-related design and implementation flaws by ensuring simple, strong security controls are available to every developer. An integrity check of software products is included to facilitate organizational verification of software integrity after delivery.

###Refactoring
Code refactoring is a “disciplined technique for restructuring an existing body of code, altering its internal structure without changing its external behavior,”6  undertaken to improve the nonfunctional attributes of the software. Advantages include improved code readability and reduced complexity to support maintenance. There are two general benefits:
* **Maintainability** > It is easier to fix bugs/defects when the source code has been written so that it is easy to understand and grasp. This might be achieved by reducing large routines into a set of individually concise, well-named, single-purpose methods. It might also be achieved by moving a method to a more appropriate class or by removing misleading comments.
* **Extensibility** > It is easier to extend the capabilities of an application if it uses recognizable design patterns and provides some flexibility where this may not have existed previously.

###Unit Testing
Designing unit testing is a challenging task for the development team. The unit test infrastructure and architecture need to be designed during Sprint 0 of the project. The unit tests could cover all layers of the application or target only certain layers. Design decisions for each unit test should be made at the Sprint 0 Meeting with the developers. During this meeting, the Scrum Master, technical lead, and developers should decide on the scope of the unit test for every Sprint scope item.
Unit tests should be included in the definition of “Done” for the requirement. When a developer makes the code ready for the Sprint’s releasable software, this indicates that the unit tests scoped for the code are also ready and included in continuous integration. Continuous integration means that unit tests are executed every time automated test builds are generated from the code repository. If one of the unit tests should fail during execution, the continuous integration mechanism sends emails to the project team every time it tries to execute the test, until the problem is resolved.

###Continuous Integration
Continuous integration is the practice of constantly merging all code from all team developers into the project’s trunk and building a testable, deployable product. Continuous integration should be run once a day at a minimum, and on every code commit at a maximum. Continuous integration increases the quality of the software by reducing the defect escape rate, and decreases maintenance and sustainment costs.
Continuous integration tools can be set up to notify the development team of any failed build. This enables the team to resolve immediately small integration issues early, before they become large or multiple issues just prior to a release/deployment.

When complemented with **automated unit testing**, code quality inspection tools, and vulnerability scanning tools, continuous integration becomes an even more powerful tool for the Agile Team. Automated unit tests identify problems early and prevent integration defects from piling up, reducing risk to release candidates and product deliveries. Automated code quality inspection tools and vulnerability scanning tools can identify poor coding practices, code violations, and security violations, without the need for additional developer code review. Continuous integration increases code quality and reduces bugs in the deployed software.
Guidelines for successful continuous integration include:

* Providing the ability for a “one-click-build”
* Executing automated builds at every commit or at least once daily
* Achieving 60-percent unit test code coverage is the target, with anything above 70 percent considered exceptional
* Provide automated notification to the entire development team when a build or unit test fails.

###Code Reviews
There are two primary benefits of **code reviews**. First, any bug found during inspection is cheaper to fix then (by orders of magnitude) than if it is found later in the process. Second, a team that is practiced in inspecting the code tends to be able to embrace the Agile principle of collective code ownership. All of the code (and any bugs identified) are the responsibility of the team, rather than a specific individual. This mindset results in a tighter, higher-quality product.

Collaborative code reviewing tools, such as Atlassian’s Crucible, which is a part of our SmartSuite environment, provide the ability for inline comments for code with informative feedback. Agile teams use code reviews to identify and fi bugs and weaknesses that may have been overlooked. Code reviews also enable senior developers to mentor junior developers on how to write better quality code.

Code reviews are performed for all code changes and should be included in the team’s software development workflow. When developers complete coding for a task, the status of the task becomes “code review,” and the Technical Lead is notified by automated email. Code is not included in the next build or made available to the test team unless the Lead Developer reviews the code with the developer present. If rejected, the task returns to the developer. If approved, the task status changes in the scope tracker to include the code in the next test build. The team should decide which of the following elements will be included in the team’s code review practice:

* Changed code
* Results of security and code quality scans
* Test case for the capability
* Functionality.

###Test-Driven Development
TDD is a software development practice that aggressively increases code quality and testability, and integrates well with the iterative nature of Agile and the process of refactoring code. Both small and large Agile teams can use TDD. It asks developers to write a test first, then produce only enough code to pass that test, then refactor the code to integrate into the existing codebase in an elegant way. Round after round, this practice continues building a robust, tested body of code.

TDD is performed in a series of Sprints for a release cycle. It is **not a testing methodology**; it is a software development technique. The objective is 100-percent coverage for the software that is built and maintained. The TDD test suite is executed once a day, as part of the continuous integration practices for unit test environments, and checks the state of the software. A previously working broken module is identified when TDD tests are automatically executed during a continuous integration build on the development servers.

###TESTING
Testing incremental functionalities of the product developed by the Agile Team involves reviewing the User Stories to ensure they meet the definition of “Done,” are considered complete, and have passed the acceptance testing criteria. Preparing for testing activities includes any artifacts required to successfully execute testing, such as the scripts, code, data, etc. The objective of any testing activity is to determine whether the incremental product developed satisfies the intended requirements and also proves to be a testable component. Along with Functional and Regression Testing activities, Automated Testing, and Acceptance Testing are also performed.

###Functional Testing
The team performs **functional testing** to ensure that the functional behavior of the product (or system) corresponds to its specifications, which involves testing one component at a time. Unit Testing focuses on testing the smallest individual units or components of the build, application modification, or system, to verify that each component is built to design specifications. Functional testing is performed after the component has been unit tested to verify functionality against the requirements and specifications, before system and integration testing.

###Regression Testing
The team performs **regression testing** to isolate and resolve any errors or defects introduced during modifications based on change requests. This testing verifies that the component still meets its specified requirements and no adverse effects have been identified as a result of implemented changes. Regression testing focuses on executing test scripts and/or scenarios in functional and non-functional areas of a system after changes have been made; ensuring the product/system still meets its specified requirements, and will not fail when deployed to the operational environment or adversely affect code that is currently in production. The Agile Team should conduct a degree of regression testing at the end of each level of testing to ensure that any defects corrected during each testing segment have not caused additional defects.

###Automated Testing
**Automated testing** must be considered part of the software development cycle. The tests themselves are an integral part of software development because they help minimize time spent debugging and help the team identify and resolve issues before users do. Prior to committing code, the code should be thoroughly subjected to automated test, and those tests should be committed with the code. This helps team members ensure their work is compatible with the code being committed. The entire automated test suite should be run against all code changes before that code is committed to ensure that there are no conflicts with other areas of the project.
When a bug is found in the system, the developer committed to fixing the bug should follow the following steps:

1. Write a unit test that expects the specific failing behavior not to occur
2. Run the test, which should fail because the bug will still be in the code
3. Fix the bug
4. Run the unit test to ensure the test now passes.

This practice ensures the bug can never be reintroduced into the system without being caught by the automated test suite.

###User Feedback or Acceptance Test
Successful Agile projects regularly put new software in front of the users for immediate feedback. This does not require a deployment to a production server but does require a demonstration or test server to which users have access and can use to try out new features still in development. Making this environment available increases communication between the users and the Agile Team. If features are found to be off track, the developers can start over, with only the loss of a Sprint’s worth of work versus 6 months or more if discovered later. This has the added benefit of showing users that while you may not have had a deployment recently, you are making progress on the highest priority request.