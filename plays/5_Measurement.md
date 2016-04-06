
# Measurement

The complexion of measuring work changes -- possibly significantly -- on an agile delivey project. But, it does not disappear.  Work must still be tracked and progress communicated. 

Planning, status, and metrics - Oh my!
=========================================
> *Working software is the primary measure of progress.*

## Play - Estimate your work
Estimation on software projects can be difficult, costly, and time-consuming. We must acknowledge that an estimate _is an estimate_.

The image below is a thought experiment comparing the accuracy of an estimate and the effort required to obtain it.  It is meant to show that, regardless of our invested effort, an estimate will never be completely accurate and may run the risk of becoming less accurate if we "overthink" things.  Our goal is always to find the balance between effort and accuracy, achieving a "good enough" estimate as quickly as possible.

The agile community has embraced a technique called **relative estimation** to approach this balance.

| _Estimation accuracy v. effort_ |
|   :-----------------------------------:   |
|![07 044 13_008b](https://cloud.githubusercontent.com/assets/5417850/10046744/93296d1e-61d8-11e5-8855-d619c3bbcbd6.jpg)|


## Play - Use relative estimation to achieve "good enough" estimates
Relative estimation is a concept that those new to the agile world often struggle with, but it simply means "compare two things to each other."  It has proven to be a very quick way to get |


Thinking of work in this way taps into some instinctual skills we have ingrained in our human DNA.  We have evolved over millenia to make fairly snap judgments regarding the size, the speed, and the danger of stimuli.  While not perfect, these snap judgments have proven accurate enough to ensure our survival.  
Considering the thought experiment above, using relative estimation techniques is able to get us fairly high on the estimate accuracy scale with very minimal effort. |




![07 044 13_007b](https://cloud.githubusercontent.com/assets/5417850/10046741/93204824-61d8-11e5-9b93-b9e06705eb22.jpg)

###Practice - Estimate size with story points
Story Points are unit-less measures of relative size used to capture estimates for software delivery. Most Agile teams employ a scale using the Fibonacci sequence when applying points to a given story (1, 2, 3, 5, 8, 13…). Many Booz Allen Agile teams have found this scale useful because the gaps in the sequence become incrementally larger as the numbers increase. These nonlinear sequences work well because they reflect the greater uncertainty associated with estimates for larger units of work. Determining size relates to the scope of the effort and to estimate size, the following three questions help formulate the team’s assessment:

1. How much work is there?
2. How hard is the work?
3. What is the level of risk?

For example, the team may need to deliver a capability that is extremely easy but will require many hours of work, and at the same time, it must deliver another capability of equivalent size that might be considered complex but will require relatively fewer hours.
A User Story estimated to be 8 Story Points is roughly four times as big in terms of combined effort, complexity, and risk as a User Story estimated at 2 Story Points. It is extremely important to note that Story Point estimate values should not be used to compare across Agile teams. The estimated value of 5 presented by one team could easily equate to an estimated value of 13 by another team. Story Points are used in a variety of ways on Agile projects, but certainly, the most common use is to estimate the Product Backlog.


### Managing for the near term, the Sprint
The most essnetial element for sprint planning is a groomed, prioritized backlog.  This backlog will serve as the guide for work to be discuss and agreed upon during sprint planning.  A groomed backlog does not mean there are exhaustive details around the user stories.  These details will emerge in  in the sprint plannning meeting as well as enoug understand to start the sprint and elborate more during execution. These discussions could lead to changes in the initial estimates the team may have developed when reviewing the backlog in preparation for the meeting.

Once there is clarity around the user stories, they are broken into tasks to complete the user story within the sprint timebox (whatever has been agreed upon at team chartering).  Once again, the act of planning the execution of the user story brings a deeper level of understanding to the team.  An additional benefit of composing tasks, is re-examing the user story and determinging if it is truly one or many user stories.  

The estimating exercise will inform the sprint plannig process as to what work can be accepted into the sprint.  As a team work is accepted that is well understood and ready to be estimated, then the team will determine what will fit into the sprint timebox based on previous velocity (story points) or days in the sprint (ideal days).   The measurement of progress in the sprint is captured in a burndown chart and the kanban boards provides more granual information on user story status (blockers and journey toward completion).

### Managing for multiple Sprints (e.g. a Release)
A release is built from one to many sprints.  Therefore the process of release planning is a scaling of  the sprint planning and measurrement process but with less detail at a higher level. Releases often look at assigning Epics to one or many sprints, with high level understanding of the user needs and work estimates.  The most important Epics are executed first to give the user the most value first.

For release planning, the most time and elboration should be spent on the most high value items, as assessed by the users.  As the sprints progress, each will be deliverying items with deminishing value.  Therefore, the most effort in estimation and detailed planning should be conducted on the first sprint, with continued elboration to gain details as the sprints progress.  As the sprints as executed, the work is evaluated at the end to repriorotize the backlog as needed, as well as determine if the product is ready for release.  

The progress of releases will be measured by burnup charts as described above.


### Executing a Strategy (e.g. multiple Releases)
Just as the release is based upon muliple sprints, the strategy is based on muliple releases which would comprise a roadmap. The burnup charts from multiple releases can show patterns to determine the long term ability to sustainably execute the strategy. The burnup charts can show if work is often added late in the release, or if work is removed as it will not be ready or has become irrelvant.  



## Play - Communicate the plan and status

> *The most efficient and effective method of conveying information to and within a development team is face-to-face conversation.*




Software development project teams recognize that the most effective and productive means of communication is a face-to-face conversation. Encouraging powerful, personal conversations requires strong facilitation and leadership skills from the Delivery Team Lead/
Scrum Master. Using an outside facilitator (such as an Agile Coach) may be useful from time to time. Agile teams may also employ a communication method such as Information Radiators to display and convey progress both within the team and to outside stakeholders.

### Information Radiators
When using the **Information Radiators** method of communication, we recommend placing tracking charts in a conspicuous place in or near the team’s general working area so that the team and any interested parties can easily view their progress. These charts, along with other visual aids, such as a storyboard (illustrates user interactions about the product) and visual representations of passing tests or code reviews, result in Information Radiators. Using this type of communication can both inform and motivate an Agile Team, because members can visually track whether they are on pace to execute the activities delegated for the
Sprint. Team members often enjoy updating the radiators when they have completed additional work. However, to be effective, the radiators must be kept up-to-date and have buy-in from the entire team.

### Meetings
**Meetings** provide the opportunity to assess where the Agile Team is within each Sprint and to evaluate the team’s progress toward realizing the project’s goals and objectives. Integrating Agile into the project lifecycle processes depends on a high level of interaction among the Delivery Team, Value Team, and the client. Table 3 provides an overview of the types of meetings that the Agile Team can employ during its project’s lifecycle.

####Table 3: Communications Meetings 

| Meeting | Main Purpose | Frequency | Delivery Team | Value Team/Client | 
| ------- | ------------ | --------- | ------------- | ----------------- | 
| Release Planning | Scoping, Acceptance Criteria, User Story Designs for Product Backlog, Release Plan | Once per Release (may occur quarterly) | Scrum Master, Development Team, SMEs | Product Owner |
| Sprint Planning | Product Backlog Review, Prioritization of User Stories, Sprint Plan, Sprint Backlog | Once per Sprint | Scrum Master, Development Team, SMEs | Product Owner |
| Sprint Review | Completed User Story Review, Feedback, Review of the Definition of Done, Demonstration of New Features, Fix Defects | Once per Sprint | Scrum Master, Development Team, SMEs | Product Owner |
| Sprint Retrospective | Evaluation, Potential Improvements, Impediment Log Review | At the end of each Sprint | Scrum Master, Development Team, SMEs | Product Owner |
| Daily Standup | Identification of Risks, Project Team Progress, Burndown Chart Reviews, Obstacles/ Impediments/ Resolutions, User Story Reviews | Daily | Scrum Master, Development Team, SMEs | Product Owner | 



## Play - Collect Metrics

> *At regular intervals, the team reflects on how to become more effective, then tunes and adjusts its behavior accordingly.*




The overall objectives for collecting and analyzing applicable measures, for any measurement program, are to promote continuous improvement, increase productivity, enhance product quality, and adopt effective and efficient practices. Metrics that are captured, reviewed, and analyzed prove to be very useful for Agile teams in many ways: they provide a continual evaluation of the progress made in delivering product features to the client and can be used to redirect product-related priorities. Agile metrics can also evaluate task completeness in terms of what has been done or not been done. When results are communicated to team members and the client, the greater understanding of what is being measured and why reinforces Agile principles.

Measures collected during execution of a Sprint include Velocity and Effort Variance, Sprint Burndown Chart, Defect Backlog Severity, and Requirement Volatility. These measures are submitted to Booz Allen’s organizational measurement repository, DataDrill, and reviewed and evaluated by the Systems Review Board (SRB), and will become the recommended metrics for Agile development firm wide.

### Practice - Velocity and Effort Variance
Metrics used to communicate the degree to which User Stories are being completed, as well as the corresponding effort, can be captured through the Sprint Effort Backlog, User Story Progress Indicator, and Velocity. **Velocity** (number of Story Points the team completed within a single, time-boxed Sprint) and **Effort Variance** (at the Sprint level) help to forecast schedule risks and provide a basis for future estimates that can be applied to development activities. Effort Variance is the percentage difference between the planned hours to complete the User Stories in that Sprint (as defined by the definition of “Done”) versus the actual hourly effort.
The development team sizes the User Stories at the start of the Sprint, estimates the number of hours required to develop and unit test the User Stories, and then distributes the work over the duration of the Sprint(s). Key factors to note:
* If the Effort Variance is above 15 percent, but Velocity remains on pace, a cost overrun risk may occur.
* If the project team is behind pace against its backlog of User Stories, but on pace against its Effort Estimate, the Sprint completion date may be at risk, or a cost overrun risk may emerge.

Figure 8 and Figure 9 provide examples of metrics captured for both Sprint Velocity and Sprint Effort Backlog and User Story Progress.

**FIGURE 8: VELOCITY, 4-WEEK SPRINTS**

![07 044 13_014b](https://cloud.githubusercontent.com/assets/5417850/10046746/932b30ea-61d8-11e5-9165-6ec0345900f3.jpg)

**FIGURE 9: SPRINT EFFORT BURNDOWN AND STORY POINT PROGRESS**

![07 044 13_015b](https://cloud.githubusercontent.com/assets/5417850/10046747/932cb460-61d8-11e5-9fbc-939be474bd9f.jpg)

### Sprint Burndown Chart
The **Burndown Chart**, illustrated in **Figure 10**, is a popular technique for communicating progress of the project’s Agile-based plan in relation to Sprint planning processes. Project teams may estimate activities and track progress based on the number of effort hours planned to develop and unit test the functionality of a feature in a given Sprint. Key factors to note:
* “Actual Hours Remaining” is driven by the project’s definition of “Done” developed for each User Story.
* At the end of each Sprint, the project team should calibrate the points in the Sprint with actual hours expended to develop a Velocity measure.

**FIGURE 10: SPRINT BURNDOWN CHART**
![07 044 13_016c](https://cloud.githubusercontent.com/assets/5417850/10046749/9335a7d2-61d8-11e5-8dba-4f0fea337141.jpg)

### Severity of Defect Backlog
The **Defect Severity** indicator, which can be created from data in the defect (or work item) tracking system, reflects the backlog of defects/User Stories stratified by severity. Client focus is typically on allocating higher severity, or older defects, to a near-term release or Sprint, but this should be a value-based decision made by the Product Owner. As part of the Sprint planning meetings, project teams should review this type of data with the client to determine which defects/User Stories will be allocated to subsequent Sprints.
Allocating defects to future Sprints helps to develop better predictive estimates for development effort, set expectations for the testing team, and provide the Value Team with insight into the expected pace of backlog resolution. Figure 11 on the next page provides an example of metrics captured for Planned Defect Backlog Resolution by Sprint.


**FIGURE 11: PLANNED DEFECT BACKLOG RESOLUTION BY SPRINT**
![07 044 13_017b](https://cloud.githubusercontent.com/assets/5417850/10046750/93374862-61d8-11e5-8bf8-e38e6b4815fc.jpg)

### Requirement Volatility
The working principles of Agile development embrace scope changes between Sprints. However, once a Sprint is planned and scheduled, volatility in the scope baseline within that specific Sprint will affect other constraints and introduce risk. **Requirement Volatility** can be measured on programs implementing an Agile development lifecycle.

For example, consider the following scenario regarding re-planning efforts before conducting each Sprint:

* A release grew from a baseline of 100 Story Points to 117 over the course of 4 Sprints.
* The project team changed 11.1 percent of the baseline before the final Sprint of the release, which should be considered a risk.

In iterative development, it is common for project teams to try to squeeze an additional new functionality into the final Sprint of a release (instead of following the best practice of allocating defect fixes to the next release). Figure 12 provides visualization of requirement volatility captured for each Sprint. Note that there is an increase in volatility from Sprint 3 to Sprint 4.


**FIGURE 12: REQUIREMENT VOLATILITY FOR SPRINTS IN A RELEASE**

![07 044 13_018c](https://cloud.githubusercontent.com/assets/5417850/10046751/9338124c-61d8-11e5-94f5-1ee492a7e1ce.jpg)

