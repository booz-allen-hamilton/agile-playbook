## Delivery

Agile teams are biased to action and are constantly seeking ways to deliver more product and more often. This section describes how agile teams work together to produce value that satisfies their stakeholders.  

> Deliver working software frequently, from a couple of weeks to a couple of months, with a preference to the shorter timescale.

> Agile processes promote sustainable development. The sponsors, developers, and users should be able to maintain a constant pace indefinitely.

> Simplicity--the art of maximizing the amount of work not done--is essential.

### Play: Start with Scrum

*Start with Scrum for agile delivery, but with an eye for "agility"*

Scrum is the most popular delivery framework for agile teams to use, by far; so much so that it’s often confused for “agile” itself. Scrum is a powerful, lightweight product delivery framework that has existed for 25 years. The definitive description of the framework is maintained by its creators in the Scrum Guides (Scrumguides.org). Because the Scrum Guides are such well-maintained and well-used resources, we won’t try to explain everything about Scrum here.

![The Scrum framework](https://github.com/booz-allen-hamilton/agile-playbook/raw/master/graphics/04.031.16_Scrum.png)

Scrum was developed to rapidly deliver value while accommodating the changes that are inevitable in product delivery. It's also meant to create a predictable pace for the team. 

Traditionally, a product is designed, then developed, then demonstrated or released to the customer. This occurs mostly as a sequence and over long stretches of time. Often, the customer is unhappy with the result and wants changes. Since we are so late in development, changes found after release are typically very costly. Scrum, however, incorporates frequent demos and feedback to mitigate surprise requirement changes. All the project work gets cut into short development iterations known as sprints. Scrum emphasizes that work planned in sprints must be small, well understood, and prioritized.

Each sprint is typically 1–4 weeks long (and stays consistent for a given team). During a sprint, the delivery team chooses the high-value work it can complete; the team focuses on just that work for the sprint’s duration. At the end of each sprint, the team demonstrates the working software it produced. During the demo, the team gathers feedback that helps shape the direction of the product going forward.

Practically, this means that design decisions are not made way ahead of time, but rather right before or even during active development.  Instead of having heavy, top-down design, design emerges and evolves over several iterations: develop, demo, gather feedback, incorporate feedback, develop, demo…

Over the course of several sprints, a picture of progress and direction emerges. Customers and management are kept informed through progress charts (see Measurement section) and end-of-sprint demos. It becomes easy to keep everyone informed while avoiding many pitfalls of micromanagement.

If Scrum is followed, many of the traditional problems associated with complex projects are avoided. The frequent feedback prevents projects from spending too much time going in the wrong direction. Furthermore, because of Scrum’s iterative nature, projects can be terminated early (by choice or circumstance) and deliver value to the end user.

Iteration—trying something and looking at it—is core to how Scrum operates. Scrum is built on three pillars: transparency, inspection, and adaptation.

##### Transparency
Many of the challenges teams face boil down to communication issues. Scrum values keeping communication and progress out in the open; doing things as a team; being transparent. The fact that Scrum’s ceremonies (Sprint Planning, Daily Standup, Sprint Review, and Retrospective) are intended for the whole team speaks to the importance of transparency.

##### Inspection
Inspecting things is how we know if they're working. Everything on a Scrum team is open to inspection, from the product to our process.

##### Adaptation
As we inspect things, if we think we would benefit from doing it differently, let’s try it! We can always adjust again later. Notably, Scrum’s Sprint Review ceremony gives us an explicit, regular opportunity to adapt based on how the product is coming along; the Retrospective ceremony does the same for how our team is working.

Scrum is widely used by a variety of development teams from those working on highly complex systems with an unknown end, through Operations and Maintenance patching.  The key to using this method is ensuring the maintenance of a groomed backlog and allowing for the flexibility needed in this short learning cycle.

> **Anti-Pattern  - No process** >  In environments where we are used to doing work in our own swim lane, or a single person possesses most the knowledge, its easy to skip defining processes,  The team needs to find ways to work together which often take the form of a process.  Repeatable well understood processes for regularly occurring tasks help the team move faster, reduce stress, and integrate new team memebers.  A process needs to be understood by the entire team and perhaps documented for it to work.  The repeatable tasks are often defined during team chartering and revisisted at retrospectives.   Some common processes to reflect on:
- Who checks our work?
- When and how do we deploy our software?
- How do we avoid becoming single threaded on a capability?
- How do we track our work?  Do we need a tool?
- What is our defect tracking process?


### Play: Seeing success but need more flexibility? Move on to Scrumban

*If Scrum is too restrictive or there are too many changing priorities within a sprint, consider Scrumban to provide the structure of ceremonies with the flexibility of delivery.*

Scrumban is derived from Scrum and Kanban (described below, in the next play) as the name would suggest. It keeps the underlying Scrum ceremonies while introducing the flow theory of Kanban.

Scrumban was developed in 2010 by Corey Ladas to move teams from Scrum which is a good starting point in agile, to Kanban, which enables flow for delivery on demand [Ladas 2010].  Kanban focuses on flow, but it does not have prescribed meetings and roles—so we borrow those from Scrum in this Scrumban model. The primary difference versus Scrum is that the sprint timebox no longer applies to delivery in Scrumban.

Instead, the team is constantly prioritizing and finishing things as soon as possible. In Scrumban, we keep Scrum’s cadence just to have our ceremonies so we don’t miss out on planning together, showing our work, and having a time for reflection.

A strict work-in-progress limit (WIP limit) is set to enable team members to pull work on demand, but not so many things that they have trouble finishing the work at hand. Scrumban has evolved some of its own practices.

Examples of unique practices to Scrumban include the following:

 - *Bucket-size planning* was developed to enable long-term planning where a work item goes from the idea bucket, to a goal bucket, then to the story bucket. The story bucket holds items ready to be considered during an on-demand planning session.
 - *On-demand planning* moves away from planning on a regular cadence, instead only holding planning sessions when more work is needed. Items to be pulled into the Kanban board are prioritized, finalized, and added to the Kanban board.
 
 Scrumban is useful for teams who are very familiar with their technical domain and may have constantly changing priorities, e.g.  a team working on the same product for an extended amount of time.  The flexibility of Scrumban allows for the back log to be reprioritized quickly and release the product on demand.


### Play: If you are ready to kick off the training wheels, try Kanban
*Try Kanban on only the most disciplined teams and when throughput is paramount.*

Kanban is a framework adopted from industrial engineering. It was developed to be mindful of organizational change management, which is apparent in the four original principles:

- Start with existing process.
- Agree to pursue incremental, evolutionary change.
- Respect the current process, roles, responsibilities and title.
- Leadership at all levels.

So, in Kanban, you will not (inherently) be receiving a bunch of new titles, or using much new vocabulary.

In 2010 David Anderson elaborated with four "Open Kanban" practices tailored for software delivery:

- Visualize the workflow.
- Limit WIP.
- Manage flow.
- Make process policies explicit.
- Improve collaboratively (using models and the scientific method).

In Kanban, you fundamentally want to make all of your work visible, continuously prioritize it, and always flow things to Done. This is great for a software team that issues several new releases per week, or per day. A pitfall, however, is that if priorities are allowed to change too often, no work will ever get done. So, be mindful about finishing things and not starting too many things.

Kanban is appropriate for teams ready to self-regulate, rather than rely on timeboxes. The practices require discipline to enable flow.  An Operations and Maintenance team with a small backlog could benefit from Kanban, as it would enable delivery of small items as needed and ensure all issues are getting to a done state.  In addition, mature agile teams with a highly automated pipeline could use Kanban as a way to enable quick flow of value to production.
