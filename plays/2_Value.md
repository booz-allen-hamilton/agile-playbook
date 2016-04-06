# Value 

> Our highest priority is to satisfy the customer through early and continuous delivery of valuable software.

> *Welcome changing requirements, even late in development. Agile processes harness change for the customer's competitive advantage.*

> Business people and developers must work together daily throughout the project.

-----
Play- Share a vision inside and outside your team
-----

The vision is the foundation upon which product decisions are made.  When at critical junctures, turn to the visiosn to help determine which direction will help the vision become a material reality.  At the team and individual level, the vision provides a common mission to rally around, and help understand the long term goals, as well as incremental goals.

###Practice - Product Vision Statement
The vision for the project should be encapsulated in a Product Vision Statement created by the product owner.  Akin to an ‘elevator pitch’, or quick summary, the goal of the Product Vision Statement is to communicate the value that the software will add to the company. It should be clear and direct enough to be understood by every level of the effort, including project stakeholders. The Vision Board by Roman Pichler is nice, simple template for forming this statment (http://www.romanpichler.com/tools/vision-board/)

//TODO image of vision board from that link

###Practice - Product Box
Product Box is another way to try to crack into the product's vision. You might try this exercise as an alternative to working with the Vision Board. This is a great way to engage a whole team in the conversation around the vision and value of the project at hand, and have some fun together while doing so.  While there are many versions of this idea, Innovation Games is a well-known one. As described there, "\[Ask your stakeholders\] to imagine that they’re selling your product at a tradeshow, retail outlet, or public market. Give them a few cardboard boxes and ask them to literally design a product box that they would buy. The box should have the key marketing slogans that they find interesting."  (http://www.innovationgames.com/product-box/)  We have also seen this work nicely by imagining your product is appearing on the App Store; what would the description, icon, screenshots, and reviews look like?


###Practice -  Roadmap
Most teams need a Product Roadmap to understand high-level objectives and direction for the project.  We think of this as the project's North Star. If we've deviated disinctly from it -- we should have a good reason, and we probably need to update the roadmap. Be sure to include the ultimate project goals in the Roadmap, keeping in mind their value added and the desired outcomes from the customer’s point of view.  It should loosely encapsulate the the overall vision and give a sense for when capabilities will be delivered, or intersecting milestones are going to occur.  The roadmap should probably cover the next 6-12 months, and only in broad strokes. Your team will have to talk through rough sizing of work and prioritization during the creation process. You're not building a schedule; but you are trying to pain a *plausible* picture. Be sure to build this together, or at least review and revise it together. Too many roadmaps are built by leadership, and they never have buy-in from the team.

###Practice -  Release Map
Once the Roadmap is complete, a Release Plan may be created for the first release.  Each release should begin with the creation of a Release Plan specific to the goals and priorities for that release.  This ensures that the value being added to the project is consistently reviewed and if necessary, realigned, to maximize the overall value and efficiency of development.   Like the Product Roadmap, the Release Plan should include a high level timeline of the progression of development, specific to the priorities for that release only.  The highest value items should be released first, allowing the stakeholders visibility into the progression of the work.


##Play - From Vision to Action. Build a backlog

Once we have and share our vision, we understand the big stuff... but we have to turn this to action quickly. A core practice for agile teams is to have a *backlog* of work. In this context, a backlog is a prioritized set of all the desired work we want to do on the project. 

###Backlog Basics
Treat your backlog as a “catch all” - any item that moves the team ahead to a final product or project goal can be added to your backlog. New features, defects, abandoned refactoring, meetings, and other work are all game to be placed in there. Additionally, keep in mind that your backlog will evolve in detail and priority through engagement with the end user . Your backlog should be a living, breathing testament to your product as you will be iteratively refining your backlog as your build your product. Product Backlog items are updated until all features of that product are delivered, which may occur through multiple releases during the project lifecycle. 

###Backlog Creation
A backlog is made of epics and user stories. User stories are simply something a user wants, and they're sized such that we understand them well; epics are bigger than that and we need to break them down further into a capacity that the team can actually execute. Generally, anyone can add something to the backlog; but the product owner "owns" that backlog, overall -- setting the priority of things, deciding what we really should be working on next. 

###Practice -  Product & Sprint Backlogs
A *product backlog* is a prioritized list of product requirements (probably called user stories), regularly maintained, prioritized, and estimated using a scale based on Story Points. It represents all of the work we may want to do for the project, and it changes often. We have not committed to deliver the full scope captured in the product backlog.

A *sprint backlog* is a detailed list of all the work we've committed to doing in the current sprint -- just a few weeks of work. Once we set it up in sprint planning, it remains locked for the duration of the sprint -- no new (surprise!) work should be added. It should stay up to date by the whole team (at least daily), and items should be marked complete based on the team's agreed Definition of Done.

Tools like JIRA facilitate having these backlogs.

-----
Play - Be informed by real users
-----
> Welcome changing requirements, even late in development. Agile processes harness change for the customer's competitive advantage.

###Practice -  Define Personas 
Personas can be used to get started with the requirements gathering process.  Each persona should capture the user and their individual needs.  Create a template with an area to draw a picture of the user, and separate spaces to describe the user personally, but also describe their desired goals, use cases, and desires for the software.  
Persona goals can then be used to create Epics, which will lead to user stories.  … User Story Creation -> Discuss difference between “I need the software to have one button for each department in my business” and “I need to be able to access each department in my business from the software”.  Can reuse the diagram they already have about bad vs good user stories.  The Product Owner should play an active role in ensuring that the User Stories will ultimately deliver the desired value to the stakeholders by driving the communication of business value at key times like Sprint Planning and Release Planning, but also as a day-to-day integrated member of the development team, available for conversations and consulting as progress is made.
End result: Backlog creation ….transition into next topic

// TODO images of personas/persona template


###Practice - Epics and user stories
+Component
+Definition
+Value Statement
--Outlines and communicates the work to be completed and what value delivering this epic or story will bring to a specific persona/user. 
--Format: As a (user role/persona) I need to be able to (deliverable), so that I can (end result/value). 
+Assumptions
--Aspects that may or may not impact and/or support your future deliverable that you need to assume exist 
+Acceptance Criteria 
---An outlined list of granular criteria that must be met in order for the story or epic to be fully delivered and adequately tested and verified. 

###Epics
Both epics and user stories are made up of the same components, all that differs between the two is their level of granularity. User stories make up an epic and are a breakdown of an epic. See the example below: 
Epic: Couch cushions
Value Statement: As a BAH employee I need the ability to sit on cushions of the blue couch, so that I can comfortably sit on and and utilize the couch. 
Assumptions: The frame of the couch exists.
Acceptance Criteria: how many, dimensions, color, fabric, placement, fill 
User Stories: There’s no right or wrong way to break down an epic, but for purposes of this example we would suggest creating a story for each couch cushion. We’ll use the center top cushion as our example.
 Value Statement: As a BAH employee I need the ability to sit on cushions of the blue couch, so that I can comfortably sit on and and utilize the couch. 
Assumptions: The frame of the couch exists.
Acceptance Criteria: how many, dimensions, color, fabric, placement, fill 

###User Stories 
User Stories depict high-level definitions of requirements that address specific functionality of the product and are planned and executed across a series of Sprints (tightly time-boxed events that include repetitive development cycles). To create value-driven stories that accurately reflect the client’s requirements, think of the acronym DEEP: 
Detailed enough so that everyone understands the need. The User Story should be sufficient for the Delivery Team to provide an Estimated value of the amount of effort it will take to implement a User Story. (Stories near the top of the Product Backlog can be estimated more accurately than those near the bottom.) The Product Backlog should contain those stories that are considered Emergent—reflecting current, pressing, and/ or realistic needs. And, of course, the Product Backlog should be Prioritized so that everyone understands which stories are most important now and require implementation. Most agile teams use the concept of User Stories to help define how the work will be accomplished.
The Product Owner and client, assisted by the Delivery Team, develops User Stories to define the descriptive requirements of a feature or capability that will mold the product’s functionality. User Stories are identified and prepared amidst the project’s lifecycle and generally focus on what should be accomplished and why. Describing the functionality in the User Story should be at a high level, so it can easily be broken down into workable development tasks and sufficiently detailed to be useful for estimating purposes. 



####Strong v. Weak User Stories


| **Strong User Stories Are…** | **Weak User Stories Are…** | 
| ---------------------------- | -------------------------- |
| - Developed and prioritized by the Product Owner | - Developed without designating the specific user or user group that will receive value from the story’s |
| - Written from the user’s perspective, implementation and employ user roles | - Created with limited Product Owner involvement |
| - Simple and concise, with clear alignment to business value | - Missing a description of the business value |
| - Entry points to a conversation on how the implementation activities can be decomposed | - Technical specifications which don’t link to the user’s point of view |
| - Written with easy to understand success criteria | - Open-ended with no means to validate acceptance |
