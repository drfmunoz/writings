##  CH2: Roles for the scalable technology organization

A common cause of failure in scalability and availability is lack of clarity in responsibilities of people.

### The effects of Failure

Lack of clarity in roles and responsibilities means that some things won't get done because they miss an owner.

At the other end of the missing owner spectrum from the "missing an owner" problem is the case where multiple organizations or people are given the same goal. **Note that this is not the same thing as "sharing a goal"**. Sharing a goal is good, because "sharing" implies cooperation. Rather, what we are describing here is he **existence of multiple owners without clarity as to who owns which actions** to achieve that goal and sometimes without understanding that another group or person is working on the same thing.

This creates a long-term resentmet between organizations and destroy employee morale. Few things will destroy morale more quickly than a group believing that it is fully responsible but failing to deliver on a task or project becuase the group members assumed someone else owned a part that did not complete.

What usually happens is that the teams become polarized and wast even more time in policitac infighting, and the final, probably delyaed result isn't materially better than if a single person or team had the responsibility to craft the best solution with the input of other teams.

**On delegation**: Defining roles and responsibilities within organizations, you are creating a blueprint of delegation. Delegation, broadly speaking, is the act of empowering someone else to act on your behalf. **You can delegate anything you like, but you can never delegate the accountability for results**. At best, the team (or individual) to which you delegate can inherit that responsibility and you can ultimate fire, promote, or otherwise reward or punish the team for its results, but **you should always consider yourself accountable for the end result.**


### Executive responsibilities

#### CEO

The CEO is the final decision maker and arbiter of all things related to scale. The CEO's job is to ask the right questions, to get the right people involved, and to solicit the right ouside help or advice to arrive at the right answer.

The CEO's job is to understand some of the basics (the equivalent of the financial statements mentioned previously), to know which questions to as, and to know where and when to get help.

_Ask questions and look for consistency in explanations_ : When you are unable to distinguish fact from perception, look for consistency in answers.

Seek outside help: Seek help from friends or professionals who are proficient and knowledgeable in the are of scale.

#### CFO
Resposible for budgeting, which is informed by capacity planning, a very important part of successfully scaling a system.

The budget needs to be large enough to allow the company to scale to the expected demand by purchasing or leasing servers and hiring the appropriate engineers and operations staff.

#### Business unit owners, general managers, and P&L owners

Forecast demand and the impact of the PnL.

#### CTO
CTO generally more focused on the science or technology of the product. The CTO/CIO must create the technical vision for the company overll. For the purpose of our discussio, within a growth company that vision must include elements of scale. 

The CTO/CIO is responsible for the deveopment of the culture and processes surrounding scalability that will help ensure that the company always stays ahead of end-user-demand.  There roles absolutely need to delegate resposibilities for certain aspects of decision making around scalability as the company grows.

The term "lead from the front" is nevers more important than in this context, and the vision does not need to be deeply technical. Equally important is that the CTO have some business acumen. Unfortunately, most technologists do not learn about business, finance, or marketing in their undergraduate or graduate courses.

A CTO should be able to analyze and understand the relationship between the income statement, the balance sheet, and the statement of cash flow. In a technology-centric company like an internet firm, the CTO will often have the largest budget in the company.


### ICs
Ensure that the company has enought people to cover for:
* Architecture
* SW engineering
* Monitoring and production (Ops)
* Infrastructure and RE
* Testing and QA

The goal is to bring enough people to cover the functional areas of building a product. This doesn't prescrive a functional organization, but rather a role to be filled. 

Note: In general, align the organizations with the products to enable product process and product discovery.

#### Architecture Responsibilities

The role of the architect is to ensure that the design and the architecture of the system allow for scale in the timeframe appropriate to the business. They are responsible for creating the set of architecture standards by which engineers design cide and implement systems.

Companies use many different titles to designate the individuals who are focused on designing the technology architecture, including software architect, system architect, scalability architect, enterprise architect, and even agile architect. These roles tend to focus on one of two areas.
1. Software Architecture, which is primarily concerned with how the software is designed and structured.
2. System Architecture, which is primarily concerned with how the software is deployed  deployed and supported on the the hardware (or VM)

#### Engineering Responsibilities

Engineersa rea "where the rubber meets the road". Engineers are the chief implementers of the scalability mission and the chief tuners of the product platform. Responsible for Adhering to the company's architectural standard, create low-level design, and implement it in code. They trully understand the limits of the system as implemented.

#### DevOps
Development and Operations => Facilitate the interactions between the software development teams and the technical operations team. Usually responsiblefor deploying, running, and monitoring the systems that create the company's revenue. 

Given that the team interacts with how the system runs every day and has daily insights into system utilization data, these team members are uniquely qualified to identify bottlenecks within the system and to design software with deployment in mind. 

Usually devops is responsible for development/testing environments, build scripts, deplyment scripts, monitoring solutions, log file aggreagation, and development or testing tools. 

#### Infrastructure Responsibilities
Set of skills unique enough that they are not needed on a daily basis on the agile teams, but rather required across many agile teams. Sometimes they are embedded, but often they work on a centralized infrastructure teams that support multiple engineering teams.

Can include DBAs, network engineers, system engineers, storage engineers. They are often responsible for defining which system will be used, when systems should be purchased, and when systems should be retired.

#### Quality Assurance
Individuals who are primarily responsible for testing an application to ensure it is consistent with the company's desired product outcomes (KPI) will also play a role in advanced testing for scale. Ensure that the release of new functionlity doesn't have an adverse effect on existing functionality. QA professionals need to be aware of all the changes going on around them so that they can ensure any scale-related testing done is updated on a timely fashion. These folks must also be focused on automated testing rather than manual testing. Not only must the product scale, but the processes by which they are test must scale to run efficiently as new features are added.

#### Capacity Planning Resposibilities
This role can reside anywhere, but they need access to up-to-date information regarding systems, product, and platform performance. Capacity planning is a key to scaling efficiently and cost-effectively. 

Scalability is the ability to scale independently of bigger and faster systems or the next release of an application server or database.

### When roles are missing!!

Maslow's Hammer (also known as the "law of the instrument") dictates that you will use the tools that you know to fix a problem rather than the best tool -> When all you have is a hammer, everything looks like a nail. Having the right skillsets and roles help preventing poor decisions that may proof constly in the long run.

### A tool for Defining responsibilities

RASCI -> responsibility assignment chart, stands for Responsible, Accountable, Supportive, Consulted, and Informed,

* R: Responsible -> The person responsible for completing the project or initiative
* A: Accountable -> Person to whom R is accountable and who must approve the work before it is okay to complete. Sometimes referred as the Approver.
* S: Supportive -> People that provide resources to complete the project or initiative.
* C: Consulted -> People that have data or information that can be useful in completing the project.
* I: Informed -> People that should eb notified, but do not need to be consulted or provide input in the project.

Ideally, in any case, there will be a single R and a single A for any given initiative. By holding a single person or organization responsible, you are abiding by the rule "one back to pat and one throat to choke". "Distributed ownership is ownership by no one".


An A should not sign off on an R approach until such time as the R has actually consulted with all of the appropriate people to develop the right course of actions.

You can add as many C, S, and I as you may want and who add value or who are needed to complete any given project. 

Warning: Young companies often assume that everyone should feel involved in every decision or be informed of every decision. This information mechanism simply does not scale, however, and results in people reading emails rather than doing what they should be doing to create shareholder value.

### In summary

* Role clarity is critical for scale initiatives to be successful
* Overlapping responsibilities create wasted effort and value-destroying conflicts.
* Areas lacking responsibilities create vacuums of activities and failed scale initiatives.
* The CEO is the chief scalability officer of the company.
* The CTO/CIO is the chief technical scale office of the company.
* RASCI is a tool that can help eliminate overlap in responsibility and create clear role definition. RASCI is developed in a matrix. R=Responsible, A=Accountable, S=Supportive, C=Consulted, I=Informed.












