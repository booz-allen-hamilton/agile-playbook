## Measurement

Measurement affects the entire team. It is an essential aspect of planning, committing, communicating, improving, and, most importantly, delivering.

### Play: Make educated guesses about the size of your work

It is important to understand what you are committing to and acknowledge when you do not. Agile teams seek to discover this understanding through the process of estimation.

One of the historical challenges of software estimation is the perception of precision. When a feature is estimated as “273 FTE hours,” it unintentionally gives a very false sense of precision and confidence in that estimate. In reality, a manager asked five different people to provide estimates across 150 requirements and summed them up.

Agile teams apply several simple practices to drive conversation, quickly expose what they collectively understand or don’t understand, and get some numbers that are approximately right instead of precisely wrong.

#### Practice: Use relative estimation

Relative estimation is a concept that those new to the agile world often struggle with, but it simply means “compare two things to each other.” If you’ve ever said something like, “Hey, this tree is twice as tall as that tree,” you already know how to do it.

When we think about estimating software, we recommend agile teams do so in terms of size. Software size is intended to capture, all at once, the:

1. Amount of work
1. Difficulty of the work
1. Risk inherent in the work.

When paired with relative estimation, it results in questions like, Is this feature as complicated as the other feature we built last week? Or, If we take on this feature, is it more risky than this other feature? When work items are similar enough across these questions, we give them the same number on a scale (see table below) that the team has previously selected. As work items differ, the team discusses those differences to understand just how different the work is, relatively, and give a corresponding number from that same scale.

##### Example relative estimation scales

| Name | Examples |
| ---- | -------- |
|  Modified Fibonacci | 1, 2, 3, 5, 8, 13, 20, 40, 100 |
| SNTB | 1, 2, 3, 100 |
| SSW | 1, too big, no clue |
| Powers of 2 | 1, 2, 4, 8, 16, 32 |
| T-shirt sizes | XS, S, M, L, XL |

These are just a few examples of scales we’ve seen teams use at Booz Allen. The most popular is the Modified Fibonacci scale because it was documented in a fantastic book (Agile Estimating and Planning by Mike Cohn) and is sold on estimation card decks. But, its popularity is for good reason: The nonlinear sequence works well because the gaps reflect the greater levels of uncertainty associated with estimates for bigger, more unknown pieces of work. More mature and disciplined teams often move toward simpler scales, such as small numbers, too big (SNTB) and same-sized work (SSW); in these cases, they essentially seek to know if work is small and understood, or if more discussion is required before commitment. Don’t try to look up SNTB or SSW; we made those names up.

##### What do we call these numbers?

Generally, agile teams call these unit-less measures of software size “story points,” or simply “points.” We recommend that teams avoid the temptation to continue to estimate in hours, even when deliberately using relative scales, because the perception to stakeholders is often a higher degree of certainty than there truly is. At one point, “ideal hours” were offered as an alternative to story points. An ideal hour is a mythical hour where you can work, uninterrupted, with all the knowledge and resources at your fingertips to get the job done. In practice, we find this causes too much confusion among the team and stakeholders—someone inevitably confuses an ideal hour estimate with an actual hour from reality.

#### Practice: Estimate as a team

A generally accepted practice among the agile community is to have the team make estimates together. This practice allows the team to discover how well work is understood, encourages knowledge sharing, builds team cohesiveness, and fosters buy-in.

One of the most popular techniques for having these team conversations to obtain estimates is Planning Poker (mountaingoatsoftware.com/agile/planning-poker). The gist of it is that the team talks about its work in a structured (but fun) way. It is based on a popular expert-based method called “wide-band delphi,” but we encourage you to provide chips and salsa.

There are other methods (e.g., Affinity Estimation, Magic Estimation), and more are created all the time. What do they all have in common? They get the team to make the estimates together, they drive conversation, and they expose uncertainty. And numbers pop out that are just good enough to move forward.


### Play: Use data to drive decisions and make improvements

Across many of our highest performing teams and programs, we've found a common love of data.  The best software practitioners really are geeks about it.  And why not?!  Data is objective.  Data tells a story.  Data is awesome.

Agile teams should use data to drive important decisions, commitments, schedules, and improvements

> **Anti-Pattern Collecting data without purpose** > Any data collected should be intentional and with purpose to improve the current process.  Collecting the same data because you always have, is waste.  Review what you do collect and how it improves the system.


#### Practice: Use the past to predict the future

An important input to any planning process is the team’s capacity for doing work. In traditional capacity planning, this may look a lot like the sum of your team’s *planned* work hours during a given period. The trouble with this is you are making decisions solely on estimates and focusing entirely on the individual people on the team rather than the team itself.

In contrast, agile teams predict how much work they can collectively accomplish by continuously looking back at how much work they have accomplished. Yesterday’s weather is the best predictor of today’s weather (unless you live on the East Coast of the United States).

> **Anti-Pattern - Taking partial credit** >  Have you ever felt like you're super busy, but you're not getting many things finished? This happens to agile teams, too. It's tempting to quickly start all the current tasks on deck. But, code isn't really valuable until it's running and the user can try it. Since delivering value should be our primary measure of progress, our time is better spent taking things to Done rather than starting more things. Taking partial credit for work does not help the team improve and deliver value.  Inspect why the team is doing this, if there are blockers to completion, those blockers should be addressed rather than starting new work.  

##### Velocity (and throughput)

For most agile teams practicing some variation of Scrum, they should measure their velocity. Velocity is the amount of work the team has historically been able to deliver in a single sprint. We usually recommend using three to seven sprints’ worth of data to produce a rolling average of your velocity each time you walk into a planning meeting.

For agile teams that are moving toward a more Kanban-style delivery, the analog to velocity is throughput. Throughput is the amount of work the team is able to deliver over some period of time. A Kanban team may measure throughput in terms of hours or days.

Some teams may get value in tracking their velocity in a Velocity Chart, example below.

**FIGURE : VELOCITY CHART**

![](https://github.com/booz-allen-hamilton/agile-playbook/raw/master/graphics/04.031.16_Velocity.png)

> **Anti-Pattern - Using Velocity to compare across teams** > Throughput and Velocity are unique to every team. Said differently, _you cannot compare teams based on their velocity measures_. Relative estimates are completely dependent on the team that is doing the estimating - one team's 1 might be another team's 5. In practice, we've found that efforts to standardize estimation scales across multiple teams tend to diverge fairly quickly.  Teams should be compared based on the value they are delivering per sprint and the predictability of their delivery.

##### Kanban metrics borrowed from lean manufacturing (cycle time, lead time, response time)

Kanban teams utilize several additional metrics from the manufacturing world because Kanban emphasizes the flow of work through the system to produce valuable outcomes. These metrics help understand how well the system is working.

| Metrics | Definition |
| ------- | ---------- |
| Cycle Time | Average time per work item (the inverse of throughput—think about it!) | 
| Lead Time | Average time it takes to deliver an item from the moment work starts |
| Response Time | Average time it takes to begin work on a single item from the moment it is added to the backlog | 

Note: These are "time per item" metrics. The average is calculated across a sample of your work items.

##### Team predictability: Commitment Variance

Commitment variance is a predictability measure of your team’s ability to deliver on its commitments.

In essence, it is the percentage ratio of the team’s delivered work to the team’s committed work, averaged over time. For example, if a team commits to delivering 10 points in a sprint, but it actually delivers 12, the commitment variance for that sprint is 12/10*100 or 120%. The team has delivered 120% of its commitment.

If your team’s commitment variance tends to be less than 100%, you may consider requiring the team to commit to no more than its previously delivered velocity instead of its rolling average velocity, for several sprints. This practice is literally called “Yesterday’s Weather.” Once the team becomes more predictable, you may consider returning to a rolling average velocity for planning.

> **Anti-Pattern - Extending the sprint** > Often and inevitably, a challenge will arise where extending a single sprint will look like a plausible solution.  And why not?  For decades, we've grown accustomed to sliding schedules "to the right."  Maybe the team did not complete all of the work that they signed up to do, or maybe priorities drastically changed in the middle of the sprint.  Or, even more simply, maybe there is a holiday in the sprint.

> The answer to this question should almost always be _No_.  The team's sprint cadence is an essential piece of their rhythm and predictability. If you're not sure why the sprint is coming up short, that's a good thing to talk about at the retrospective.

### Play: Radiate valuable data to the greatest extent possible

Agile teams are known for their **information radiators**.  These are Big Visible Charts.  Ron Jefferies said it best, "display important project information not in some formal way, not on the web, not in PowerPoint, but in charts on the wall that no one can miss" \[Jeffries 2004\].

Certainly, some team environments pose a challenge in radiating information in this way. The trend toward globally distributed teams alone is an impediment. In these cases, the teams will have to explore other methods for radiating information and discover practices that work for them.

#### Practice: Burndown chart

Burndown charts are the go-to chart for agile teams. Simply stated, they track the amount of work the team has “left” on any given day, and—hopefully—the team’s workload goes down most days. We have found burndown charts to be most effective for tracking progress “within a sprint.”

Coming out of a planning meeting (e.g., sprint planning), the team can sum up the estimates for all of the work in the sprint backlog. When stories are complete, according to the team’s definition of done, points are burned down to show progress.

In some cases, once a team gets started on the work, it learns a particular item is bigger than originally thought. That, too, is captured in the burndown chart as the points going up.

**SPRINT BURNDOWN CHART**

![Burndown Chart](https://github.com/booz-allen-hamilton/agile-playbook/raw/master/graphics/04.031.16_Burndown.png)

Note that for teams practicing Kanban, a burndown chart may not be the most useful way to observe progress. For that, we recommend a cumulative flow diagram (described below).

##### Burndown patterns

Keep an eye on the shape of your team’s burndown charts. We’re fans of this article from RallyDev, which speaks to this idea: [help.rallydev.com/reading-burndown-chart](http://help.rallydev.com/reading-burndown-chart).

#### Practice: Burnup chart

Burnup charts are quite similar to burndown charts; they just go in the opposite direction. Whereas the burndown chart shows the team “burning down” their work to 0, the burnup chart shows work being completed and moving up. Likely the largest difference between the two is the addition of a target line in the burnup chart. As the team progresses, burning up progress, the total amount of work it expects to get done also is graphed. This chart is an excellent way to display changes in scope or understanding over time.

It is for this reason that we recommend teams use burnup charts for tracking bigger efforts across multiple sprints, such as for a large epic or feature delivery, or a multi-sprint plan time horizon (sometimes called a “release” or a “product increment”).

**MULTI-SPRINT BURNUP CHART**

![Burnup Chart](https://github.com/booz-allen-hamilton/agile-playbook/raw/master/graphics/04.031.16_Burnup.png)

#### Practice: Visualize work in process using a cumulative flow diagram

Cumulative flow diagrams show where work is in your process. Over time, you can see how much work you have in any given stage of your product flow. This diagram is an excellent tool for teams to visualize their WIP. It is easy to observe bottlenecks, understand your team’s level of focus, and get a sense of some of the Kanban metrics described previously (cycle time, response time, lead time).

For teams of all shapes and sizes, WIP should be managed and kept to a minimum to ensure continuous flow of value and reduce wasted effort.

**Cumulative Flow Diagram**

![Cumulative Flow Diagram](https://github.com/booz-allen-hamilton/agile-playbook/raw/master/graphics/04.031.16_CFD.png)

### Play: Working software as the primary measure of progress

> Working software is the primary measure of progress.

Yes! In any discussion of measurement, it is essential that we not lose sight of an agile team’s true measure: the regular and continuous delivery of working, high-quality software that is potentially shippable.

#### Practice: Technical debt

Technical debt is a useful metaphor for “stuff that will come back to bite you in the long term.” Technical Debt is the cost of fixing the structural quality violations that, if left unfixed, put the business at serious risk. The data on technical debt provides an objective frame of reference for the development team. They also provide a way for the development and management team to have tradeoffs discussion. These could be defects left unresolved, code that is not reviewed or unit tested, or shortcut architectural decisions. What technical debt truly means to your team is a worthy discussion to have often.

Whatever you determine to be your technical debt, you should track it. You are going to have to pay it off sometime. And, like interest, the cost of change increases over time as your technical debt ages and grows.

Here is a short list of code quality indicators that are worth tracking:

* Unresolved defects over time, sliced by severity
* Unit, integration, and functional test code coverage
* Frequency and duration of builds
* Code review coverage
* Code coupling and cohesion metrics.


#### Practice: Value predictability

We’ve previously discussed velocity as a measure of the team’s capacity to deliver work. Because of its name, we sometimes forget that it is slightly different than the velocity of the physical sciences (in physics, velocity is a measure of speed and direction). In the agile world, velocity has no sense of the team’s direction.

Velocity is valuable input for planning, but it is not exactly an indicator of progress. To help get a sense of the team’s direction and the value of its output, we turn to the value predictability measure. This measure is a comparison of the actual value delivered and the planned value delivered.

Coming out of a planning session, the team’s Product Owner assigns a value estimate to each work item (usually on a simple relative scale, like 1 to 10). Then, coming out of a review, the team’s Product Owner identifies how much value the team delivered for each item on the same scale. Both of these sets of values are summed and tracked over time.

Note, this is a measure that we’ve seen used by teams at Booz Allen, but it is also quite similar to a measure popularized by SAFe: the program predictability measure. SAFe suggests that this type of metric could be useful at higher levels of an organization and recommends a predictability measure between 80% and 100% as being “predictability sufficient to run a business” (scaledagileframework.com/metrics/#P2). We see no reason to disagree.

#### Practice: Customer satisfaction

The simplest approach we’ve seen teams successfully use to track customer satisfaction is to just ask for a letter grade (e.g., A, B, C, D, E) coming out of all demonstrations and deliveries. Tracking these letter grades over time can give you a really solid sense of how successful the program is at delivering the value it says it will deliver.

One caveat: In cases where customers may churn a lot on direction, there is a slight risk that the customer satisfaction metric could be low in spite of the team’s best efforts.
