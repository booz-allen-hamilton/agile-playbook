
# Measurement

> Working software is the primary measure of progress.

Yes!
In any discussion of measurement, it is essential that we not lose sight of an agile team's true measure: the regular and continuous delivery of working, high quality software, that is potentially shippable.

However, agile teams also use data to plan and commit to work; to communicate progress, quality, and changes in direction; and to continuously improve both themselves and the product that they are creating.


## Play - Estimate your work as a team, and make team commitments based on facts

// Make educated guesses about the size of your work, and continuously measure how fast you can get it done.

It is important to understand what you are committing to and to acknowledge when you do not.

### Practice - Use relative estimation to discover whether you understand your work

Relative estimation (http://guide.agilealliance.org/guide/relative.html) is a concept that those new to the agile world often struggle with, but it simply means "compare two things to each other."  If you've ever said something like "Hey, this tree is twice as tall as this other tree," you already know how to do it.

When we think about estimating software, we recommend agile teams do so in terms of its _size_.
Software size is intended to capture, all at once, 
*(1) the amount of work*, 
*(2) the difficulty of the work*, and 
*(3) the risk inherent in the work*.
When paired with relative estimation, this manifests itself in questions like 
"is this feature as complicated as the other feature we built last week?" or 
"if we take on this feature, is it more risky than this other feature?"
When work items are similar enough across these dimensions, we give them the same number on some predetermined scale (see table below).
As work items differ in one or more of these dimensions, the team discusses those differences to understand just how different the work is, relatively, and would give a corresponding number from that same scale.

#### Some popular scales used in relative estimation

| Name | Examples | Pro | Con |
| ---- | -------- | --- | --- |
|  Modified Fibonacci | 1, 2, 3, 5, 8, 13, 20, 40, 100 | Many Booz Allen Agile teams have found this scale useful because the gaps in the sequence become incrementally larger as the numbers increase. These nonlinear sequences work well because they reflect the greater uncertainty associated with estimates for larger units of work. | asdf |
| | 1, 2, 3, 100 | asdf | asdf |
| | 1, Too big, No clue | asdf | asdf |
| Powers of 2 | 1, 2, 4, 8, 16, 32 | asdf | asdf |
| T-shirt sizes | XS, S, M, L, XL | asdf | asdf |

#### What do we call these numbers?
Generally, agile teams call these unit-less measures of software size _story points_, or just points.
Alternatively, _ideal hours_ can be used but run the risk of being confused with "actual hours". 
(An ideal hour is an hour where you can work, uninterrupted, with all the knowledge and resources at your fingertips, to get the job done.)

#### How do we get these numbers, exactly?

One of the most popular techniques for having these conversations and obtaining estimates is Planning Poker (https://www.mountaingoatsoftware.com/agile/planning-poker); the gist of it is that the team talks about their work in a structured (but fun) way.

// TODO: Talk about additional approaches for obtaining estimates, e.g. affinity estimation or magic estimation

### Practice - Measure your team's capacity, and use this as input for planning.

An important input to any planning process is the capacity of the team doing the work.
In traditional planning, this may look a lot like a formula resulting in the sum of the planned work hours for each of your team members during a given period.
In contrast, agile teams predict how much work they can collectively accomplish by continuously looking back at how much work they have accomplished.
Yesterday's weather is the best predictor of today's weather (unless you live on the east coast of the United States).

// TODO: Talk about *velocity* and *throughput*

| Capacity measure | Description | Used when |
| ---------------- | ------- | --------- | 
| Throughput       | Number of points that a team can complete within a given period of time | asdf |
| Velocity         | Throughput for a sprint | asdf |

**FIGURE : VELOCITY CHART (Tim note: needs update; needs to add Thruput chart)**

![07 044 13_014b](https://cloud.githubusercontent.com/assets/5417850/10046746/932b30ea-61d8-11e5-9165-6ec0345900f3.jpg)

// TODO: Discuss **Committment Variance** (previously called Effort Variance...)

**Committment Variance** is the percentage difference between the planned work versus the actual amount of work to be completed.
The development team sizes the User Stories at the start of the Sprint, estimates the number of hours required to develop and unit test the User Stories, and then distributes the work over the duration of the Sprint(s). Key factors to note:
* If the Effort Variance is above 15 percent, but Velocity remains on pace, a cost overrun risk may occur.
* If the project team is behind pace against its backlog of User Stories, but on pace against its Effort Estimate, the Sprint completion date may be at risk, or a cost overrun risk may emerge.

// TODO: Double check those assertions above...

## Play - Make progress visible, across several time horizons

//TODO The following sections are largely unchanged from v1, but reordered.  Need to be updated for narrative flow and accuracy.

//TODO Discuss why this play is important; possibly discuss Information Radiators here (text below)

When using the **Information Radiators** method of communication, we recommend placing tracking charts in a conspicuous place in or near the team’s general working area so that the team and any interested parties can easily view their progress. 
These charts, along with other visual aids, such as a storyboard (illustrates user interactions about the product) and visual representations of passing tests or code reviews, result in Information Radiators. 
Using this type of communication can both inform and motivate an Agile Team, because members can visually track whether they are on pace to execute the activities delegated for the
Sprint. 
Team members often enjoy updating the radiators when they have completed additional work. However, to be effective, the radiators must be kept up-to-date and have buy-in from the entire team.

### Practice - For the near term (e.g a sprint)

// TODO: goal of this section is to talk about tracking work within a sprint.  Sprint Backlog and Burndown Chart

// TODO: discuss creation of Sprint Backlog; old text directly below.

As a team work is accepted that is well understood and ready to be estimated, then the team will determine what will fit into the sprint timebox based on previous velocity (story points) or days in the sprint (ideal days).   The measurement of progress in the sprint is captured in a burndown chart and the Kanban boards provides more granular information on user story status (blockers and journey toward completion).

The **Burndown Chart**, illustrated in **Figure 10**, is a popular technique for communicating progress of the project’s Agile-based plan in relation to Sprint planning processes. Project teams may estimate activities and track progress based on the number of effort hours planned to develop and unit test the functionality of a feature in a given Sprint. Key factors to note:
* “Actual Hours Remaining” is driven by the project’s definition of “Done” developed for each User Story.
* At the end of each Sprint, the project team should calibrate the points in the Sprint with actual hours expended to develop a Velocity measure.

**FIGURE 10: SPRINT BURNDOWN CHART (Tim note: this image is close; should remove reference to hours**

![07 044 13_016c](https://cloud.githubusercontent.com/assets/5417850/10046749/9335a7d2-61d8-11e5-8dba-4f0fea337141.jpg)

### Practice - For multiple sprints (e.g. a release or Product Increment)

// TODO: Goal of this is to discuss tracking across multiple sprints.

// TODO: Acknowledge that release is kind of a misnomer (this is why SAFe 4.0 has moved to Product Increment)

A release is built from one to many sprints.  Therefore the process of release planning is a scaling of the sprint planning and measurement process but with less detail at a higher level. Releases often look at assigning Epics to one or many sprints, with high level understanding of the user needs and work estimates.  The most important Epics are executed first to give the user the most value first.

For release planning, the most time and elaboration should be spent on the most high value items, as assessed by the users.  As the sprints progress, each will be delivering items with diminishing value.  Therefore, the most effort in estimation and detailed planning should be conducted on the first sprint, with continued elaboration to gain details as the sprints progress.  As the sprints as executed, the work is evaluated at the end to reprioritize the backlog as needed, as well as determine if the product is ready for release.  

The progress of releases will be measured by burnup charts as described above.

//TODO Discuss components of a release plan

//TODO Discuss Burnup Charts across mutiple sprints; incorporate discussion of requirement volitity (below) into Burnup.  

#### Requirement Volatility
The working principles of Agile development embrace scope changes between Sprints. However, once a Sprint is planned and scheduled, volatility in the scope baseline within that specific Sprint will affect other constraints and introduce risk. **Requirement Volatility** can be measured on programs implementing an Agile development lifecycle.

For example, consider the following scenario regarding re-planning efforts before conducting each Sprint:

* A release grew from a baseline of 100 Story Points to 117 over the course of 4 Sprints.
* The project team changed 11.1 percent of the baseline before the final Sprint of the release, which should be considered a risk.

In iterative development, it is common for project teams to try to squeeze an additional new functionality into the final Sprint of a release (instead of following the best practice of allocating defect fixes to the next release). Figure 12 provides visualization of requirement volatility captured for each Sprint. Note that there is an increase in volatility from Sprint 3 to Sprint 4.

**FIGURE 12: REQUIREMENT VOLATILITY FOR SPRINTS IN A RELEASE**

![07 044 13_018c](https://cloud.githubusercontent.com/assets/5417850/10046751/9338124c-61d8-11e5-94f5-1ee492a7e1ce.jpg)

### Practice - Executing a strategy (e.g. multiple releases or Product Increments)

// TODO Introduce strategic, possibly portfolio or valuestream level measures here.

Just as the release is based upon multiple sprints, the strategy is based on multiple releases which would comprise a roadmap. The burnup charts from multiple releases can show patterns to determine the long-term ability to sustainably execute the strategy. The burnup charts can show if work is often added late in the release, or if work is removed as it will not be ready or has become irrelevant.  

### Practice - Keep an eye on your work in process (WIP)

// TODO introduce Cumulative Flow Diagrams here?

## Play - Have *valuable* meetings

// TODO reframe this section to be about (1) only having meetings that are valuable and (2) update the table to show the purpose of those meetings and why you'd have them.

**Meetings** provide the opportunity to assess where the Agile Team is within each Sprint and to evaluate the team’s progress toward realizing the project’s goals and objectives. Integrating Agile into the project lifecycle processes depends on a high level of interaction among the Delivery Team, Value Team, and the client. Table 3 provides an overview of the types of meetings that the Agile Team can employ during its project’s lifecycle.

####Table 3: Communications Meetings 

| Meeting | Main Purpose | Frequency | Delivery Team | Value Team/Client | 
| ------- | ------------ | --------- | ------------- | ----------------- | 
| Release Planning | Scoping, Acceptance Criteria, User Story Designs for Product Backlog, Release Plan | Once per Release (may occur quarterly) | Scrum Master, Development Team, SMEs | Product Owner |
| Sprint Planning | Product Backlog Review, Prioritization of User Stories, Sprint Plan, Sprint Backlog | Once per Sprint | Scrum Master, Development Team, SMEs | Product Owner |
| Sprint Review | Completed User Story Review, Feedback, Review of the Definition of Done, Demonstration of New Features, Fix Defects | Once per Sprint | Scrum Master, Development Team, SMEs | Product Owner |
| Sprint Retrospective | Evaluation, Potential Improvements, Impediment Log Review | At the end of each Sprint | Scrum Master, Development Team, SMEs | Product Owner |
| Daily Standup | Identification of Risks, Project Team Progress, Burndown Chart Reviews, Obstacles/ Impediments/ Resolutions, User Story Reviews | Daily | Scrum Master, Development Team, SMEs | Product Owner | 



## Play - Track your technical debt

// TODO does this stay?  And how should it be expanded?

##### Severity of Defect Backlog
The **Defect Severity** indicator, which can be created from data in the defect (or work item) tracking system, reflects the backlog of defects/User Stories stratified by severity. Client focus is typically on allocating higher severity, or older defects, to a near-term release or Sprint, but this should be a value-based decision made by the Product Owner. As part of the Sprint planning meetings, project teams should review this type of data with the client to determine which defects/User Stories will be allocated to subsequent Sprints.

Allocating defects to future Sprints helps to develop better predictive estimates for development effort, set expectations for the testing team, and provide the Value Team with insight into the expected pace of backlog resolution. Figure 11 on the next page provides an example of metrics captured for Planned Defect Backlog Resolution by Sprint.

**FIGURE : PLANNED DEFECT BACKLOG RESOLUTION BY SPRINT**

![07 044 13_017b](https://cloud.githubusercontent.com/assets/5417850/10046750/93374862-61d8-11e5-8bf8-e38e6b4815fc.jpg)
