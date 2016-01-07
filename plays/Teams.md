> Build projects around motivated individuals. Give them the environment and support they need, and trust them to get the job done.

> The most efficient and effective method of conveying information to and within a development team is face-to-face conversation.

> At regular intervals, the team reflects on how to become more effective, then tunes and adjusts its behavior accordingly.


### Roles in a team

//TODO jjj
- ScrumMaster
- Product Owner
- Team Member

### Team structure patterns
//TODO

#### The Cinderella Team
//TODO

#### Expanding a PO to a VT
//TODO

#### Further expanding to include multiple DTs or VTs.
//TODO

### Practices for creating team-ness
//TODO

- Chartering
- Retrospectives


### On physical proximity
//TODO
- Colocaton
- Distributed teams



### Legacy text
###RECOMMENDED AGILE TEAM STRUCTURE
Booz Allen Agile teams are cross functional in nature and work collectively to determine how and when the product will be built and delivered to the client. A standard Agile Team structure comprises a Delivery Team and a Value Team.
####ROLES AND RESPONSIBILITIES

An Agile Team includes an interdisciplinary mix of individuals. Together, they form an Agile community committed to project success. Depending on the scope of the project, the size and organization of these teams vary, as do the names and roles.

The roles listed in this playbook serve as a basic structure for organizing an Agile Team. Keep in mind that Agile projects executing a Scrum-like framework generally engage a Scrum Master, a Product Owner, and the team described in Table 1. For teams new to adoption of the Agile mindset, an Agile Coach role should also be established on the team. While not necessarily a full-time member of the Delivery Team, the Agile Coach is an experienced “Agilist,” who facilitates team events (e.g., Standup Meetings, Sprint Planning) early in the project. The Agile Coach also helps the team adhere to the Agile mindset, provides mentorship, and optimizes the processes to promote value-based delivery.


###Standard Agile Team Structure 
| Role | Description | Responsibilities |
| ---- | ----------- | ---------------- |
| Product Owner (Value Team) | Person responsible for maximizing the return on investment (ROI) for the development effort | - Prioritizes the Product Backlog, Accepts or rejects each product increment, Decides about continued development and potential shipment of incremental product, Represents the client’s perspective, Interacts with Delivery Team frequently |
| Scrum Master (Delivery Team) | Person responsible for facilitating the Scrum process (Traditional Role = Team/Technical Lead) | Manages each Sprint and associated planning, review, and retrospective, Assists in resolving impediments, Enforces time-boxed events, Ensures estimates are gathered and captures data for adjusting forecasts, Performs as the primary interface between the Delivery Team and Value Team | 
| Delivery Team Members | Cross-functional team members who are self-organizing, self-managing, and collaborative (Traditional Roles = Developers and Testers) | Commits to Sprint assignments, Collaborates to execute daily activities related to development, testing, and other project efforts, Ensures each User Story meets the criteria established for definition of Done | 


###The Delivery Team
The Delivery Team is a cross-functional group that possesses all the skills and resources necessary to deliver valuable, high-quality, tested products to the client. In a software context, a typical team consists of developers, architects, testers, and systems engineers. This team works together in a highly communicative and collaborative manner, taking collective ownership of the product delivered and resolving any bugs/defects that may be encountered. High-performing Agile teams are self-organizing—able to drive themselves toward delivering the highest value software for the client.
###The Value Team
The Value Team’s responsibility is to communicate and represent the client’s needs by defining priorities and acknowledging acceptance when the product meets the intended need. The Value Team can be as small as one person (often called the Product Owner, a key stakeholder who also represents the client), but a larger team may consist of a group of users, business analysts, and members of the Program Management Office. A chief responsibility of the Value Team is to own the Product Backlog—the prioritized list of all the work yet to be completed. The Value Team must also provide regular feedback about the working product the Delivery Team demonstrates. To attain the maximum benefit of Agile development, the Value Team must be readily available to the Delivery Team to respond to questions and provide feedback.
###ROLES BASED ON TEAM SIZE
Our experience shows that a cross-functional 10-person team is the preferred maximum team size. This size is also supported by PMI-ACP guidelines and follows general Scrum guidelines. Each project team has a dedicated Scrum Master (Team/Technical Lead). An overall Product Owner acts as a client representative and subject matter expert (SME) to validate acceptance of the delivered software or product. As the project size scales beyond the 10-person maximum, work can be segmented into multiple teams following the “Scrum of Scrums” concept—teams are organized according to how the software is architected (e.g., one Agile Team for integration working on interoperability), with the assumption that the architecture can be divided into multiple integration points. This is consistent with Conway’s Law4  regarding segmenting sub teams in the image of the architecture that will be delivered.

Roles and responsibilities vary if the team is particularly small or large, because it is easier to implement Agile with small team constraints versus attempting to scale broadly. Sub roles can be incorporated into the Agile Team structure, based on small or large projects. Suggested configurations include:

* **Small Project** (six team members or fewer) > Scrum Master role may overlap with Project Manager and Agile Coach responsibilities; team members possess multiple areas of expertise (e.g., Analyst may also serve as a Tester); Product Owner remains a distinct role.
* **Large Project** (15 team members or more) > Agile Coach must have experience with large Agile projects; the project is likely to have multiple Product Owners, with a single Lead Product Owner assigned for the entire system; Team Product Owners are treated as a proxy for that single voice.

When large projects are involved, facilitate collaboration among the Product Owners, Team Leads, and Development staff through the “Scrum of Scrums” practice. In a large team environment, it may be inefficient for all staff to attend Daily Standup Meetings.

Restrict these meetings to four or five members, and conduct multiple standup meetings if necessary, to keep them short, focused, and effective. Finally, unique Project Manager, Scrum Master, Architect, Requirements Manager, Test Manager, Quality Assurance (QA) Manager, and Configuration Manager roles are required for the project. These norms and responsibilities should be finalized as a part of Sprint 0 activities.

**Table 2** provides a list of additional roles that may be included in Agile sub teams for both small and large projects.

#####Table 2:	Agile Sub-team Roles

| Role | Value Team/Delivery Team | Responsibilities | 
| ---- | ------------------------ | ---------------- | 
| Project Manager | Value Team/Delivery Team | •	Handles project-level responsibilities, including staffing, monitoring progress, and costing | 
| Chief Architect | Delivery Team | •	Assists with prioritizing the Product Backlog, Accepts or rejects each product increment | 
| User Interface Designers | Delivery Team | • Assists Product Owner with user interface issues and provides solutions; Provides prototypes as potential input to Sprint planning (if needed) |
| Test Manager | Delivery Team | •Oversees testing activities of the Scrum Development Team |
| Software Developer | Delivery Team | •	Provides demonstrations of working software; Builds extensive suites of automated testing to prevent breaks in existing functionality during future software development Sprints | 
| Software Tester | Delivery Team | • Assists Value Team in defining acceptance criteria for Product Backlog items; validates criteria have been met through incremental testing efforts | 
| Information Assurance Specialist | Value Team | • Plans, coordinates, and implements required security measures | 
| Business and/or Requirements Analyst | Value Team | • Works with Agile Team members to define requirements in smaller increments; Interacts and communicates with Delivery Team (developers and testers) | 
| QA Manager | Value Team | • Provides independent review of processes, procedures, and plans |
| Configuration Management (CM) Manager | Value Team | • Addresses integrity of work products, baselines, version control, and continuous integration | 
| Requirements Manager | Value Team | •	Works with Agile Team regarding requirements specifications and allocating/de-allocating requirements | 
| Functional SMEs | Value Team | • Provides technical knowledge and skill set related to efficient and effective execution of Agile development practices | 
| Agile Coach | Independent  of Delivery and Value Teams | •	Performs the role of team facilitator, skilled in requirements elicitation and systems delivery | 



