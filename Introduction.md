# Introduction

Agile is the de facto way of delivering software today. Compared to waterfall development, agile projects are far more likely to deliver on time, on budget, and having met the customer’s need. Despite this broad adoption, industry standards remain elusive due to the nature of agility—there is no single set of best practices.

The purpose of this playbook is to educate new adopters of the agile mindset by curating many of the good practices that we’ve found work for teams at Booz Allen. As we offer our perspective on implementing agile in your context, we present many “plays”—use cases of agile practices that may work for you, and which together can help weave an overall approach for tighter delivery and more satisfied customers.

Core to our perspective are the following themes, which reverberate throughout this playbook. We’ve come to these themes as software practitioners living in the trenches and delivering software on teams using increasingly modern methods, and in support of dozens of customers across the U.S. Government and the international commercial market.

* **Agile is a mindset.** We view agile as a mindset—defined by values, guided by principles, and manifested through emergent practices—and actively encourage industry to embrace this definition. Indeed, agile should not simply equate to delivering software in sprints or a handful of best practices you can read in a book. Rather, agile represents a way of thinking that embraces change, regular feedback, value-driven delivery, full-team collaboration, learning through discovery, and continuous improvement. Agile techniques cannot magically eliminate the challenges intrinsic to high-discovery software development. But, by focusing on continuous delivery of incremental value and shorter feedback cycles, they do expose these challenges as early as possible, while there is still time to correct for them. As agile practitioners, we embrace the innate mutability of software and harness that flexibility for the benefit of our customers and users. As you start a new project, or have an opportunity to retool an existing one, we urge you to lean to agile for its reduced risk and higher customer satisfaction.
* **Flexibility as the standard, with discipline and intention.** Booz Allen Systems Delivery uses a number of frameworks across projects, depending on client preferences and what fits best. We use Scrum, Kanban, waterfall, spiral, and the Scaled Agile Framework (SAFe), as well as hybrid approaches. But we embrace agile as our default approach, and Scrum specifically as our foundational method, if it fits the scope and nature of the work.
* **One team, multiple focuses.** Throughout this playbook, we explicitly acknowledge the symbiotic relationship between delivery (responsible for the “how”) and value (responsible for the “what”), and we use terms like “delivery team” and “value team” to help us understand what each team member’s focus may be. However, it’s crucial to consider that, together, we are still one team, with one goal, and we seek a common path to reach that goal.
* **Work is done by teams.  Teams are made of humans.** A team is the core of any agile organization. In a project of 2 people or 200, the work happens in teams. And at the core of teams are humans. Just as we seek to build products that delight the humans who use them, we seek to be happier, more connected, more productive humans at work.
* **As we move faster, we cannot sacrifice security.** According to the U. S. Digital Service, nearly 25% of visits to government websites are for nefarious purposes. As we lean toward rapid delivery and modern practice, we must stay security-minded. Security cannot be a phase-gate or an after-thought; we must bring that perspective into our whole team, our technology choices, and our engineering approach. 

### Who should use this playbook?

This playbook was written primarily for new adopters of agile practices, and it is intended to speak to managers, practitioners, and teams. While initially written as a guide solely for Booz Allen Systems Delivery professionals, it is our hope that the community will also find value in our experience. We have deliberately minimized Booz Allen-specific “inside baseball” language wherever possible. 

A Booz Allen internal addendum is also available for Booz Allen staff, with links and information only relevant for them. This is not because it is full of “secret sauce” proprietary information; rather, it is to keep the community version accessible and broadly valuable.

### How should you use this playbook?

This playbook is not intended to be read as a narrative document.  It is organized, at a high level, as follows:

1. **Agile Playbook context.** This is what you are reading now. We introduce the playbook, provide a high-level “Agile Model,” and offer some parting thoughts.
1. **The plays.** The plays are the meat of the playbook and are intended to be used as references. Plays describe valuable patterns that we believe agile teams should broadly consider—they are “the what.” Within many plays, we describe techniques for putting them into practice. Plays are grouped into nine categories: Delivery, Value, Teams, Craftsmanship, Measurement, Management, Adaptation, Meetings, and Agile at scale.

### Agile Playbook v2.0 - What's new? 

This is version 2.0 of our Agile Playbook. The first edition was published in 2013 and aided many practitioners in adopting and maturing their agile practice across our client deliveries and internal efforts. To address the regular changes happening in our industry, our firm, and the craft of software engineering, we wanted to update this material and reach an even wider audience. The following sections describe some specific changes you’ll find in version 2.0.

#### Agile at scale, and DevOps

Two big shifts seem particularly apparent since we published the first Agile Playbook. The first is the growth of agile delivery on very large-scale projects. Our clients were commonly using agile approaches on efforts with fewer than 30 delivery staff, but it’s now becoming a normal request with 50, 100, and 200 staff involved. With such size come some new quirks to keep delivery moving while living out agile values and principles at such scale. So we wanted to begin to tell that story.

The other large shift is the ubiquity of DevOps. No longer experimental, or just the domain of startups, DevOps’ promise of faster delivery and higher quality is driving teams of all sizes and missions to adopt higher levels of automation and deeper team cohesion across disciplines that previously did not often integrate. This playbook is constructed with an eye toward aiding teams adopting a DevOps mindset and common practices while referencing our firm’s DevOps Playbook.

#### Systems Delivery is bigger than it used to be!
In the last few years, not only has our business grown but also we acquired SPARC \[[Booz Allen Hamilton 2015](http://www.boozallen.com/media-center/press-releases/2015/11/booz-allen-hamilton-acquires-software-services-business-of-sparc)\]! The SPARC team is known for its deep expertise in modern agile and DevOps methods, as well as its creativity in delivering solutions integrating cloud computing, UI/UX design, mobile technologies, cybersecurity, and production operation. This playbook represents a new collaboration of our Systems Delivery thought leaders and practitioners across Booz Allen, including SPARC.

#### Best learning practices
The first playbook referred to itself as a collection of best practices, but we want to clarify that. In most cases these are best *learning* practices. If you need a place to start or you want to understand something in context, we hope this playbook serves as a valuable guide and helps you keep walking toward high performance as a team or program. But, just as guitar virtuosos or Olympic skiers have moved past the form and rules they learned in their first few weeks of practice, we expect our delivery teams to learn the values here, start with the learning practices, and eventually innovate their way toward even higher performance methods that are unique to them.

#### Publicly accessible and kept up to date more continuously
Finally, we are excited to share that this playbook will move away from a monolithic release process, and it will be shared broadly. Now and in the future, you will be able to find (and contribute to) the latest version of the Agile Playbook through GitHub at https://github.com/booz-allen-hamilton/agile-playbook. If you are reading a printed copy of this playbook, we encourage you to also check it out on the Web for the absolute latest!

### How and where can you contribute to this playbook?

We want to build this playbook as a community.  If you have ideas or experiences (or find a typo or broken link) you wish to share, we would love to hear about it.  Contributions can be sent in one of two ways:

* Pull requests
* Email us at agile@bah.com—patch files preferred, but any feedback is welcome.

We welcome feedback on the entire playbook, but we are looking for contributions in a few particular areas:

* New play or practice descriptions
* Reports or articles from the ground, completely attributed to you
* Favorite tools and software for inclusion in our tools compendium
* Additional references or further reading

Please be sure to take a look at our [style guide](../../wiki/Style-Guide) before submitting feedback.
