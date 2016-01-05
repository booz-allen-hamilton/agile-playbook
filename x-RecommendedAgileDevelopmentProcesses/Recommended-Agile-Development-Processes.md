###RECOMMENDED AGILE DEVELOPMENT PROCESSES
Providing a set of standardized processes that can be executed during the project lifecycle creates an environment for the Agile Team to operate in an iterative, incremental manner that contributes to the delivery of a quality working product for the client.
For project teams starting out with Agile implementation, Booz Allen provides a framework featuring 10 fundamental steps.

###CREATE THE AGILE TEAM
Agile teams seek to be much more than a group of talented individuals—they work collectively to own the product and exhibit high-performing, self-organizing characteristics. Get started by identifying cross-functional team members who can engage in delivering the product iteratively and incrementally. The Agile Team should be capable of—and commit to—remaining flexible, collaborative, and productive to complete all work assigned within a given Sprint. Creating a fundamental Team Charter can help sustain this commitment. If the team is new to adoption of the mindset, an experienced Agile Coach can provide significant value during this stage of the project. Some of the elements of this charter should include the following information:
*	Current Product Vision
*	Types of Meetings (when and where they will occur)
*	Methods for Planning and Estimating
*	Communication Rules (both internal and external)	
*	Agile Concepts, Strategies, and Terminologies (used by the Agile Team)
*	Engineering Rules
*	Team’s Definition of “Done” (determined during development of the Product Backlog).

###ESTABLISH AGILE TOOL ENVIRONMENT
After assembling the team, the next step is to establish the Agile environment that will be used by the Scrum Master, Product Owner, and Delivery Team. This generally involves procuring the required hardware and software, and varies based on the system, product, or components being developed, as well as resources assigned to the project, customization of infrastructure standards, and client requirements.
Software to assist the team in automating many of the steps needed to create artifacts, such as the Product and Sprint Backlogs, User Stories, and Burndown Charts, is easily accessed through Booz Allen’s SmartSuite integrated tool set. Tool standardization assists projects with startup and enhances consistent, repeatable results that facilitate the decision-making processes. For more information about SmartSuite, see Section 6.

###DEVELOP USER STORIES
The Product Owner and client, assisted by the Delivery Team, develops User Stories to define the descriptive requirements of a feature or capability that will mold the product’s functionality. User Stories are identified and prepared during the project’s lifecycle and generally focus on what should be accomplished and why. Describing the functionality in the User Story should be at a high level, so it can easily be broken down into workable development tasks and sufficiently detailed to be useful for estimating purposes.

To accomplish this task, we recommend an approach based on the “Develop User Story” process obtained from the OSP:
*	Create the User Story by taking a feature of the system or product and describing its functionality
*	Provide an initial determination of the sequence of User Story implementation based on its dependencies on other stories
*	Determine the Acceptance Criteria used to test the User Story
*	Add the User Story to the Product Backlog.

###CREATE THE PRODUCT BACKLOG
The Value Team, particularly the Product Owner, is responsible for maintaining the Product Backlog. Product Backlog items are updated until all features of that product are delivered, which may occur through multiple releases during the project lifecycle.
When creating the Product Backlog, the Agile Team must first articulate its definition of “Done” in relation to what constitutes completed backlog items. The team makes this determination during Sprint 0, when the plan and goals are laid out for the first Sprint. Definitions may change throughout the project lifecycle and can vary depending on whether the focus is a specific Product Backlog item or the overall release. Consider the following concepts when preparing the team’s definition of “Done”:

* Assess the state of the functionality’s code at the end of the Sprint
  *    Coding has been completed, functionality is ready for testing, or production releasable software is ready. (The latter is the desirable criterion.)
* Each project identifies its own definition of “Done,” but commonly referenced checkpoints are:

	  *     Code review has been performed

	  *     Security scanning has been performed

	  *     Test case is ready (if applicable)

	  *     Developer has written a unit test for approved changes

	  *     Unit test has been passed

	  *     Functional, integration, and/or regression testing have been performed

	  *     An automated functional test has been performed (if applicable).


###ESTIMATE THE PRODUCT BACKLOG
To plan for a current release, the team needs high-level initial estimates for items or capabilities contained in the Product Backlog; these estimates should be oriented toward those items with higher priorities (based on value and risk). Items with lower priorities should be estimated as part of later releases. Estimation also helps determine whether the features or capabilities are worthwhile, which tasks may need to be created to complete Product Backlog items, and how each item will be implemented. A technique described later in this playbook for estimating size is the use of Story Points for relative estimation of a feature or capability (refer to Section 5). Estimating the Product Backlog items involves input from the entire Agile Team, which may result in reprioritizing the User Stories based on sizing estimates.
#####PRIORITIZE THE WORK
Depending on your project and stakeholders, you can establish priorities in different ways. The most common method is to prioritize for “value”—an admittedly vague notion that reflects the degree of importance of User Stories to the stakeholders. The Product Owner, along with the client, determines the relative value of a User Story. However, some projects are prioritized based on risk. Because Agile project events will be time-boxed, it is best to prioritize the riskiest stories first, to give them the best chance of reaching completion. Stories related to development of the system architecture are typically assigned a high priority and are sequenced as such. Responsibility for prioritization of all Product Backlog items rests with the Product Owner but is ultimately shared by the entire Agile Team.
#####Prioritization for Value
Each capability or item in the Product Backlog has a business value, which is prioritized by the Product Owner (and team members) based on the client’s feedback. Ideally, the value of a capability is based on the financial impact distributed over a period of time, but it is difficult to estimate the financial impact of each item in the Product Backlog. In this case, the Product Owner, working directly with other members of the Agile Team, proceeds with reviewing and assigning a value to each Product Backlog item while the team collaborates to ensure the assigned value aligns with the item’s value to the client.
After all Product Backlog items have been prioritized for value, they are then ordered from High (a “must have” capability) to Low (does not return any value), with the objective to first complete those items with the highest value to the client. This technique helps to ensure that the relative priority of all items reflects the business value they provide.
#####Prioritization for Risk
Risks are inherent and prevalent when executing any software development project. An Agile Team must continually review risk, which can be associated with the business value assigned to each Product Backlog item or capability. When identifying risks, we suggest grouping them in three categories:

The Agile Team should review these risks even if business- value-based prioritization has also been used. It is important to look for high-risk items because they may either be removed from the list of Product Backlog items or moved to the top of the queue; an example would be assigning a higher priority to a high-risk but low-value capability after discussion with the client. Combining risk and value in a prioritization matrix is illustrated in **Figure 2**.

**FIGURE 2: RISK AND VALUE PRIORITIZATION MODEL**
* Schedule Risks
* Cost Risks
* Scope Risks.

![07 044 13_009c](https://cloud.githubusercontent.com/assets/5417850/10046745/932a1458-61d8-11e5-9d8e-b20c9499b605.jpg)


###PLAN THE WORK
Planning is critical to the success of Agile software development projects. Some of the most important characteristics of Agile planning include reducing risk and uncertainty (factoring new knowledge into Sprint planning), supporting decision-making (estimating to determine what functionalities are provided), establishing trust (delivering frequent reliable increments of the product), and conveying information (communicating a set of baseline expectations).

Delivering working software through well-executed planning is the primary metric demonstrating progress for any Agile Team. Each of the releases constitutes usable software, and each release provides new features that were not present in the previous release.

By delivering working software early and often, rather than as one large and encompassing delivery at completion, Agile teams increase the probability that stakeholders will receive an early ROI and lower overall risk for systems delivery. **Figure 3** compares value delivery to risk of failure (time versus value) between the Waterfall Development Model and the Agile Development Model.

**Figure 3:**

![07 044 13_013c](https://cloud.githubusercontent.com/assets/5417850/10046742/9326e1c0-61d8-11e5-8226-ad31ddbf5d53.jpg)



##### Plan the Release
When an Agile Team expects a software release to require more than a single Sprint, the team performs a process known as Release Planning (see Figure 4). Release Planning is the responsibility of the Value and Delivery teams, is facilitated by the Value Team Lead (Product Owner), and takes place just before the start of a release.

**FIGURE 4: The Release Planning Process**

![07_044_13 010d](https://cloud.githubusercontent.com/assets/5417850/10046738/931a6b16-61d8-11e5-9858-72ba13e86a3a.jpg)


The Value and Delivery teams identify features/capabilities from the Product Backlog to be delivered within a release. The teams scope the features to assess the size of the release. Dividing that size by the team’s measured Velocity (the rate at which a team delivers work in a Sprint) predicts how many Sprints are required to deliver the agreed-upon features. Sprint Backlogs capture the planned features for each release, traceable to the source requirements received from the client.

The Product Owner needs to decide whether to time-box or feature-box the release. Time-boxing the release means that whichever features are defined as “Done” will be delivered on a specified date, and is generally the preferred method implemented by Agile teams. Feature-boxing the release interjects constraints by identifying a feature or set of features required for delivery.

The complexity of the software and maturity of the team (reflected in the Velocity), among other factors, influence the expected release date and content for the software. The team may also opt to identify optimistic, median, and pessimistic release plans based on corresponding Velocity measures. Sprint by Sprint, the Delivery Team tracks progress toward a pre-defined goal. If the features requested remain static, then tracking progress is relatively straightforward. However, if scope creep occurs, it must be tracked as well. Scope changes typically occur at the end of the Sprint and are executed by adjusting the priorities of the Product Backlog items that drive future Sprints.

**Figure 5** illustrates an example of progress toward a static goal of the 100 User Stories planned for the release, with work extending over 6 Sprints. Having a well communicated definition of “Done” is imperative for this model.

#####FIGURE 5: FEATURES PLANNED FOR A RELEASE
![07 044 13_011b](https://cloud.githubusercontent.com/assets/5417850/10046743/93276776-61d8-11e5-9471-031c3847efaa.jpg)

To augment the planning process, Agile teams assigned to a large-scale development task may benefit from preparing a strategic Product Roadmap to clarify what is to be accomplished during the release planning, sprint planning, and daily planning processes. Agile projects, especially those expected to take longer to complete, generally employ a Product Roadmap that provides a coarser level of items than does the Product Backlog. This roadmap is usually a presentation of high-level features mapped to quarterly milestones projecting 6- to 18 months into the future. From a strategic and product planning perspective, the Product Roadmap takes into account major product features, technological advancements, industry cycles, and funding levels. It can be quite useful in managing the Product Backlog, which focuses more on the tactical development activities.5 

####Plan the Sprint
At the start of each Sprint, the Agile Team engages in Sprint Planning. This meeting pulls in representatives from the Value Team, including the Product Owner and the entire Delivery Team. During this meeting, the Value Team representatives review the User Stories slated for the Sprint. The Delivery Team asks insightful questions, performs some on-the-spot design, identifies risks and dependencies, and decomposes each User Story into discrete tasks that Delivery Team members can perform to complete allocated User Stories. The Delivery Team may also work with the Value Team to split User Stories into smaller slices of functionality or reprioritize the stories based on logical sequencing.

The Agile Team determines how much work it can perform in a given Sprint by forecasting selected items from the Product Backlog to be delivered during the Sprint and creating the Sprint Backlog. The focus of the Sprint is to ensure the definition of “Done” is addressed. Before a piece of functionality reaches a potentially releasable state, the team must have a common understanding of completion. During the Sprint Planning meeting, the Agile Team reconfirms its definition of “Done,” which enables the team to scope the level of work required for a given Sprint. The definition of “Done” does not change during the Sprint, but may change between Sprints to reflect improvements the team makes to its processes and capabilities in delivering the product to the client. A common definition of “Done” helps to:
* Baseline progress on work items
* Provide transparency within the team
* Expose work items that require attention
* Determine when an increment of the product is ready for release

The length of a Sprint may range from 1 day to 1 month. Although there is some flexibility in this model, extending a Sprint beyond 4 weeks begins to dilute the intended value gained by frequent, iterative demonstrations of working software. Each Sprint cycle is executed in the same amount of time. The following factors may affect the team’s Sprint planning process:
* Client
* Scope
* Funding
* Contract-mandated reviews
* Complexity
* Size and capability of the team.

####EXECUTE THE SPRINT
Each Sprint is consistent in duration, with a new Sprint starting immediately after the previous one is completed. Each Sprint cycle produces an increment of the defined product that is considered “Done,” as determined by the Agile Team. The product is designed, coded, built, and tested during the execution phase of the Sprint (time-boxed cycles of 1 month or less), based on items assigned to the Sprint Backlog. As part of inspecting the daily actions of the team’s work, there must be constant inspections to assess the progress of the team in realizing the goals of the Sprint. Remember, the entire Sprint cycle encompasses the Sprint planning process, the actual development work, the Sprint Review and Retrospective, and of course, the Daily Standup Meetings.

Refer to **Figure 6** on the following page for a high-level view of what comprises a Sprint cycle.
#####FIGURE 6: THE SPRINT CYCLE IN THE AGILE DEVELOPMENT MODEL
![07 044 13_002c](https://cloud.githubusercontent.com/assets/5417850/10046737/931a4046-61d8-11e5-99c7-444f5d0d6b00.jpg)


####Sprint Zero
The purpose of the first Sprint cycle, or Sprint 0, is to coordinate the prerequisites for subsequent development activities. Sprint 0, a high-level feature prioritization session, requires the participation of both the Product Owner and development team representatives. Team members work toward creating a preliminary Product Backlog, calibrating roles and responsibilities, and establishing the technical environment. These activities should be kept as lightweight as possible and not take longer than the defined duration for one Sprint. Remember that Sprint 0 does not result in the delivery of shippable code but sets the stage for development activities to begin in earnest with the first Sprint. For new adopters of the mindset, an Agile Coach can be helpful during Sprint 0 activities.

Sprint 0 begins with preparation of a Release Plan that scopes the release and introduces the high-level Sprint plans for the team. This process addresses the following items:
* Create Product Backlog > Prioritize the work with the Product Owner and estimate the backlog items using Story Points
* Identify Team Capacity for One Sprint > Determine how many User Stories the Agile Team can work in one Sprint
* Estimate Team Velocity for a Release > Determine Story Point capacity for a specified number of teams for a given number of Sprints
* Allocate Product Backlog into Releases > Base this allocation on the total team Release Capacity
* Sprint Planning for the Next Release > Repeat all activities for each Sprint 0 conducted for every Release.
Part of the process for Sprint 0 includes determining how each team will work to address its assignments, derived from decomposing User Stories into executable tasks and assigning Story Points. At this point, the Product Owner has prioritized and estimated the User Stories, so the more difficult tasks are executed first.

###The Agile Rhythm—Daily Standup Meetings

####FIGURE: THE STANDUP IS THE HEARTBEAT OF THE TEAM
![07 044 13_020b](https://cloud.githubusercontent.com/assets/5417850/10046752/933a2636-61d8-11e5-9125-a59b0289a996.jpg)
High-performing Agile teams work in a perpetual rhythm, with beats occurring regularly throughout each Sprint. Every day, the team conducts a Standup Meeting (time-boxed to 15 minutes or less) at the same time and location. It is not a status meeting; it is a coordination meeting. The objective of the planning and oversight activity is to evaluate execution of the Sprint Plan and to identify and resolve any issues raised, potential blockers, or impediments.

The classic format for conducting the Daily Standup Meeting is for each team member to address the following **three questions**:
1.	What did I do yesterday?
2.	What do I plan to do today?
3.	What impediments are affecting my ability to work?

The Delivery Team Lead/Scrum Master should pay special attention to the answers to the third question, because it is their responsibility to remove any impediments. When a blocker cannot be resolved with the existing resources or technologies, a **Spike** needs to be created. A Spike is an unplanned, necessary work item required to complete the Sprint successfully. Sometimes, even though a solution to the blocker is found using the Spike, it may not be a quick or short-term solution. In this case, the team should incorporate the result of the Spike into the continuous planning activities because it could potentially have an impact on the Sprint and/or the release planning.

As part of the Agile rhythm, if multiple teams or large teams are involved in the project’s activities, then it may be necessary to conduct a “Scrum of Scrums” Meeting multiple times during each week that includes a lead or representative from each team. The same three questions are posed here as in the daily meeting, but the focus should be to address each team representative’s responses instead of those of each team member.

###CONDUCT THE SPRINT REVIEW
The team conducts the **Sprint Review** at the conclusion of each Sprint. The meeting’s objective is to determine whether the goal of the Sprint (defined in the Sprint Planning Meeting) was achieved: what was done, what was not done, and what the team accomplished. This review can serve as a platform for the team to demonstrate the completed User Stories—providing an open forum for the client, stakeholders, and team members to see the work accomplished during the specific Sprint. Generally, the Product Owner is involved in these reviews, and along with the Agile Team, ensures that the incremental product demonstrated meets the definition of “Done” with respect to designing, coding, building, and testing the shippable functionality.

###CONDUCT THE SPRINT RETROSPECTIVE
The team holds a **Retrospective Meeting** after the Sprint Review and before the next Sprint Planning Meeting. The Retrospective is another time-boxed event, providing time for the Agile Team to pause and reflect on what happened and how to proceed. The goal of the Retrospective is to identify actions the team can take to improve the next Sprint or release to increase team Velocity and work output. For any action assigned to a team member, it is good practice to confirm actions were followed through to closure and to provide an acceptable improvement that can be easily adapted in the next Sprint.

Facilitating productive Retrospectives is a master skill all to itself. Some Retrospectives may be more productive than others, but all contribute to the learning process and focus on inspecting where the team has been and facilitating the team’s adaptation to continuous improvement. The classic form of the Retrospective is to ask the Agile Team **three questions**:

1. What went well?

2. What did not go well?

3. What will we do differently?

Part of standardizing the software development process outside the Scrum framework in support of the Agile mindset requires the Agile Team to adhere to common practices. Various techniques and methodologies can be employed to derive similar measures, but the specific practices that generate results and value are the practices that Booz Allen recommends. The following sections provide the newly formed Agile Team with solutions for creating User Stories, estimating effort, communicating results, developing the product, testing the functionalities, and instituting a set of standard Agile metrics