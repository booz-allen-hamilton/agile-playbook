###RECOMMENDED  AGILE DEVELOPMENT PRACTICES
Part of standardizing the software development process outside the Scrum framework in support of the Agile mindset requires the Agile Team to adhere to common practices. Various techniques and methodologies can be employed to derive similar measures, but the specific practices that generate results and value are the practices that Booz Allen recommends. The following sections provide the newly formed Agile Team with solutions for creating User Stories, estimating effort, communicating results, developing the product, testing the functionalities, and instituting a set of standard Agile metrics.

###USER STORIES
User Stories make up the Product Backlog. To create value-driven stories that accurately reflect the client’s requirements, think of the acronym DEEP: Detailed, Estimated, Emergent, and Prioritized. To expand on this concept, a User Story should be _Detailed_ enough so that everyone understands the need, including acceptance criteria that define when the User Story is considered “Done.” Without getting into implementation, the detail provided should be sufficient for the Delivery Team to provide an _Estimated_ value of the amount of effort it will take to implement a User Story. (Stories near the top of the Product Backlog can be estimated more accurately than those near the bottom.) The Product Backlog should contain those stories that are considered Emergent—reflecting current, pressing, and/ or realistic needs. And, of course, the Product Backlog should be Prioritized so that everyone under- stands which stories are most important now and require implementation.
Most Agile teams use the concept of User Stories to help define how the work will be accomplished. A User Story is essentially a business need captured and stored in the Product Backlog.

![07 044 13_004](https://cloud.githubusercontent.com/assets/5417850/10046739/931a9dc0-61d8-11e5-8d3b-514904299851.jpg)

![07 044 13_005](https://cloud.githubusercontent.com/assets/5417850/10046740/931f44ce-61d8-11e5-91b5-f25e94348b2d.jpg)

####Strong v. Weak Users 


| **Strong User Stories Are…** | **Weak User Stories Are…** | 
| ---------------------------- | -------------------------- |
| - Developed and prioritized by the Product Owner | - Developed without designating the specific user or user group that will receive value from the story’s |
| - Written from the user’s perspective, implementation and employ user roles | - Created with limited Product Owner involvement |
| - Simple and concise, with clear alignment to business value | - Missing a description of the business value |
| - Entry points to a conversation on how the implementation activities can be decomposed | - Technical specifications which don’t link to the user’s point of view |
| - Written with easy to understand success criteria | - Open-ended with no means to validate acceptance |

### STORY POINTS AND IDEAL DAYS 
One of the starkest departures from traditional planning practices is that Agile teams decouple the estimation of their work from the time it will take to deliver. In other words, Agile teams estimate how much work they have and measure how fast they complete that work to predict when they will be able to deliver.

Estimation, and in particular the estimation of software development, is an extremely difficult, often costly, and time-consuming task. Agile teams recognize that an estimate is an estimate. **Figure 7** depicts general Estimation Accuracy versus Estimation Effort. It displays the notion that at an arbitrary point in the estimation process, an estimate can no longer achieve increased accuracy. Several relative estimation techniques are based on size (units) rather than effort (hours or days). This playbook discusses Story Points and Ideal Days, which are both used frequently by Agile teams and are recommended Booz Allen practices when applying relative estimation approaches.
######Figure 7: Estimation Accuracy v. Effort

![07 044 13_008b](https://cloud.githubusercontent.com/assets/5417850/10046744/93296d1e-61d8-11e5-8855-d619c3bbcbd6.jpg)


![07 044 13_007b](https://cloud.githubusercontent.com/assets/5417850/10046741/93204824-61d8-11e5-9b93-b9e06705eb22.jpg)

####Estimating Size with Story Points
Story Points are unit-less measures of relative size used to capture estimates for software delivery. Most Agile teams employ a scale using the Fibonacci sequence when applying points to a given story (1, 2, 3, 5, 8, 13…). Many Booz Allen Agile teams have found this scale useful because the gaps in the sequence become incrementally larger as the numbers increase. These nonlinear sequences work well because they reflect the greater uncertainty associated with estimates for larger units of work. Determining size relates to the scope of the effort and to estimate size, the following three questions help formulate the team’s assessment:

1. How much work is there?
2. How hard is the work?
3. What is the level of risk?

For example, the team may need to deliver a capability that is extremely easy but will require many hours of work, and at the same time, it must deliver another capability of equivalent size that might be considered complex but will require relatively fewer hours.
A User Story estimated to be 8 Story Points is roughly four times as big in terms of combined effort, complexity, and risk as a User Story estimated at 2 Story Points. It is extremely important to note that Story Point estimate values should not be used to compare across Agile teams. The estimated value of 5 presented by one team could easily equate to an estimated value of 13 by another team. Story Points are used in a variety of ways on Agile projects, but certainly, the most common use is to estimate the Product Backlog.

####Estimating Size with Ideal Days
**Ideal Days** are another measure of relative size used by Agile teams. Unlike Story Points, which are unit-less, Ideal Days are expressed in terms of the ideal time it will take to complete a task (assuming a best-case scenario). Ideal Days do not equate to elapsed time and, like Story Points, must be used in conjunction with the team’s measured Velocity to obtain actual time estimations. Developers must consider the number of hours they are productive in a given work day and use that as one of the variables when estimating. It is standard practice to consider whole numbers only when estimating in terms of Ideal Days.
Agile teams may choose to use Ideal Days instead of Story Points for a variety of reasons. Because we are more accustomed to estimating in terms of time, it is often easier for project teams new to Agile to understand the concept of Ideal Days. Another strong case can be made for using Ideal Days when estimating work on the Sprint Backlog. During Sprint planning, Delivery teams generally decompose User Stories or capabilities into manageable work tasks that can be completed in fewer than 2 days. At this level, it may be more appropriate to perform Ideal Day estimation.

####COMMUNICATIONS
Software development project teams recognize that the most effective and productive means of communication is a face-to-face conversation. Encouraging powerful, personal conversations requires strong facilitation and leadership skills from the Delivery Team Lead/
Scrum Master. Using an outside facilitator (such as an Agile Coach) may be useful from time to time. Agile teams may also employ a communication method such as Information Radiators to display and convey progress both within the team and to outside stakeholders.

####Information Radiators
When using the **Information Radiators** method of communication, we recommend placing tracking charts in a conspicuous place in or near the team’s general working area so that the team and any interested parties can easily view their progress. These charts, along with other visual aids, such as a storyboard (illustrates user interactions about the product) and visual representations of passing tests or code reviews, result in Information Radiators. Using this type of communication can both inform and motivate an Agile Team, because members can visually track whether they are on pace to execute the activities delegated for the
Sprint. Team members often enjoy updating the radiators when they have completed additional work. However, to be effective, the radiators must be kept up-to-date and have buy-in from the entire team.

###Meetings
**Meetings** provide the opportunity to assess where the Agile Team is within each Sprint and to evaluate the team’s progress toward realizing the project’s goals and objectives. Integrating Agile into the project lifecycle processes depends on a high level of interaction among the Delivery Team, Value Team, and the client. Table 3 provides an overview of the types of meetings that the Agile Team can employ during its project’s lifecycle.

####Table 3: Communications Meetings 

| Meeting | Main Purpose | Frequency | Delivery Team | Value Team/Client | 
| ------- | ------------ | --------- | ------------- | ----------------- | 
| Release Planning | Scoping, Acceptance Criteria, User Story Designs for Product Backlog, Release Plan | Once per Release (may occur quarterly) | Scrum Master, Development Team, SMEs | Product Owner |
| Sprint Planning | Product Backlog Review, Prioritization of User Stories, Sprint Plan, Sprint Backlog | Once per Sprint | Scrum Master, Development Team, SMEs | Product Owner |
| Sprint Review | Completed User Story Review, Feedback, Review of the Definition of Done, Demonstration of New Features, Fix Defects | Once per Sprint | Scrum Master, Development Team, SMEs | Product Owner |
| Sprint Retrospective | Evaluation, Potential Improvements, Impediment Log Review | At the end of each Sprint | Scrum Master, Development Team, SMEs | Product Owner |
| Daily Standup | Identification of Risks, Project Team Progress, Burndown Chart Reviews, Obstacles/ Impediments/ Resolutions, User Story Reviews | Daily | Scrum Master, Development Team, SMEs | Product Owner | 




###DEVELOPMENT
The Agile Team employs multiple methods to iteratively develop the product through the creation of User Stories. These methods include secure coding standards and best practices that the team must follow, using code refactoring, applying version control methods, and using continuous integration to merge developed code. Test-Driven Development (TDD) is a software development practice that aggressively increases code quality and testability, providing another avenue for Agile teams to subject their code to strenuous code reviews and refactoring techniques.

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

###COLLECTING METRICS
The overall objectives for collecting and analyzing applicable measures, for any measurement program, are to promote continuous improvement, increase productivity, enhance product quality, and adopt effective and efficient practices. Metrics that are captured, reviewed, and analyzed prove to be very useful for Agile teams in many ways: they provide a continual evaluation of the progress made in delivering product features to the client and can be used to redirect product-related priorities. Agile metrics can also evaluate task completeness in terms of what has been done or not been done. When results are communicated to team members and the client, the greater understanding of what is being measured and why reinforces Agile principles.

Measures collected during execution of a Sprint include Velocity and Effort Variance, Sprint Burndown Chart, Defect Backlog Severity, and Requirement Volatility. These measures are submitted to Booz Allen’s organizational measurement repository, DataDrill, and reviewed and evaluated by the Systems Review Board (SRB), and will become the recommended metrics for Agile development firm wide.

###Velocity and Effort Variance
Metrics used to communicate the degree to which User Stories are being completed, as well as the corresponding effort, can be captured through the Sprint Effort Backlog, User Story Progress Indicator, and Velocity. **Velocity** (number of Story Points the team completed within a single, time-boxed Sprint) and **Effort Variance** (at the Sprint level) help to forecast schedule risks and provide a basis for future estimates that can be applied to development activities. Effort Variance is the percentage difference between the planned hours to complete the User Stories in that Sprint (as defined by the definition of “Done”) versus the actual hourly effort.
The development team sizes the User Stories at the start of the Sprint, estimates the number of hours required to develop and unit test the User Stories, and then distributes the work over the duration of the Sprint(s). Key factors to note:
* If the Effort Variance is above 15 percent, but Velocity remains on pace, a cost overrun risk may occur.
* If the project team is behind pace against its backlog of User Stories, but on pace against its Effort Estimate, the Sprint completion date may be at risk, or a cost overrun risk may emerge.

Figure 8 and Figure 9 provide examples of metrics captured for both Sprint Velocity and Sprint Effort Backlog and User Story Progress.

**FIGURE 8: VELOCITY, 4-WEEK SPRINTS**

![07 044 13_014b](https://cloud.githubusercontent.com/assets/5417850/10046746/932b30ea-61d8-11e5-9165-6ec0345900f3.jpg)

**FIGURE 9: SPRINT EFFORT BURNDOWN AND STORY POINT PROGRESS**

![07 044 13_015b](https://cloud.githubusercontent.com/assets/5417850/10046747/932cb460-61d8-11e5-9fbc-939be474bd9f.jpg)

###Sprint Burndown Chart
The **Burndown Chart**, illustrated in **Figure 10**, is a popular technique for communicating progress of the project’s Agile-based plan in relation to Sprint planning processes. Project teams may estimate activities and track progress based on the number of effort hours planned to develop and unit test the functionality of a feature in a given Sprint. Key factors to note:
* “Actual Hours Remaining” is driven by the project’s definition of “Done” developed for each User Story.
* At the end of each Sprint, the project team should calibrate the points in the Sprint with actual hours expended to develop a Velocity measure.

**FIGURE 10: SPRINT BURNDOWN CHART**
![07 044 13_016c](https://cloud.githubusercontent.com/assets/5417850/10046749/9335a7d2-61d8-11e5-8dba-4f0fea337141.jpg)

###Severity of Defect Backlog
The **Defect Severity** indicator, which can be created from data in the defect (or work item) tracking system, reflects the backlog of defects/User Stories stratified by severity. Client focus is typically on allocating higher severity, or older defects, to a near-term release or Sprint, but this should be a value-based decision made by the Product Owner. As part of the Sprint planning meetings, project teams should review this type of data with the client to determine which defects/User Stories will be allocated to subsequent Sprints.
Allocating defects to future Sprints helps to develop better predictive estimates for development effort, set expectations for the testing team, and provide the Value Team with insight into the expected pace of backlog resolution. Figure 11 on the next page provides an example of metrics captured for Planned Defect Backlog Resolution by Sprint.


**FIGURE 11: PLANNED DEFECT BACKLOG RESOLUTION BY SPRINT**
![07 044 13_017b](https://cloud.githubusercontent.com/assets/5417850/10046750/93374862-61d8-11e5-8bf8-e38e6b4815fc.jpg)

###Requirement Volatility
The working principles of Agile development embrace scope changes between Sprints. However, once a Sprint is planned and scheduled, volatility in the scope baseline within that specific Sprint will affect other constraints and introduce risk. **Requirement Volatility** can be measured on programs implementing an Agile development lifecycle.

For example, consider the following scenario regarding re-planning efforts before conducting each Sprint:

* A release grew from a baseline of 100 Story Points to 117 over the course of 4 Sprints.
* The project team changed 11.1 percent of the baseline before the final Sprint of the release, which should be considered a risk.

In iterative development, it is common for project teams to try to squeeze an additional new functionality into the final Sprint of a release (instead of following the best practice of allocating defect fixes to the next release). Figure 12 provides visualization of requirement volatility captured for each Sprint. Note that there is an increase in volatility from Sprint 3 to Sprint 4.


**FIGURE 12: REQUIREMENT VOLATILITY FOR SPRINTS IN A RELEASE**

![07 044 13_018c](https://cloud.githubusercontent.com/assets/5417850/10046751/9338124c-61d8-11e5-94f5-1ee492a7e1ce.jpg)