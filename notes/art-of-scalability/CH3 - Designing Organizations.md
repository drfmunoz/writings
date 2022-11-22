# CH3 -  Designing organizations

### Organizational Influences that Affect Scalability

-> Communication, efficiency, standards, quality, and ownership.

Communication and coordination: fundamental for any task involving more than one person.
Case on failure: Was that failure the engineer's fault for not being a superstar or was it the organizational structure's fault for making it impossible to communicate and collaborate clearly and effectively.

In the Agile software development methodology, product owners are often seated alongside engineers to ensure that product questions get answered immediately and efficiently. If not collocated, then the cost to create some value increases and as the resource pool becomes fully utilized, the company starts favoring short-term customer-facing features at the expense of long-term scalability projects.

Organizational efficiency is also driven bu the adoption of standards. An organizations that does not foster the creation, distribution, and adoption of standards in coding, documentation, specifications, and deployment is sire to suffer from decreased efficiency, reduced quality, and increased risk associated with significant production issues.

Standards such as commenting code and the discipline to do so might slip with some teams as they favor greater throughput, but at tht expense of future maintainability. Great organizations help engineers understand the value of established guidelines, principles, and collective norms.

An organization that doesn't not foster adherence to norms and standards in essence condones lowering the quality of the product being developed.

Ownership also affects the scalability and availability of a product. When many people work on the same code and there is no explicit or implicit ownership of elements of the code base, no one feels as the owners of the code. When this occurs, no one takes the extra step to ensure others are following standards, building the requested functionality, or maintaining the high quality desired in the product.

### Team size

Look for the optimal size for your organization.

No rule, but a rule of thumb: low boundary for team size is 6 and our upper boundary is 15. Fewer than 6 engineers, there is probably no point in dividing them into separate teams. For the upper bound, if there are more than 15 people on a single team, the size starts to hinder the manager's ability to actively manage and the communication between team members starts to falter.

What determines the team size you should consider the experience level of the managers. 

Base manager responsibilities: ensure engineers are productive on value-creating projects, either self-directed or by edict of management ensuring that administrative tasks, duch as allocating compensation or passing along human resources information are handled appropiately; and ensuring that managers stay current on the projects and problems they are running and can pass status information on the same along to upper management.

Junior manager: administrative and project management tasks consume her entire day. New tasks typically take longer and require more intense concentration than tasks that have been performed over and over again.

#### Experience and tenure

Tenure of the team is another factor to consider: Long-tenured and highly experienced teams require less overhead from management and less communication internally to perform their responsibilities. Both, experience at the company and as engineer is important. Long-tenured employees generally require lower administrative overhead. Experienced engineers need less help understanding specifications, designs, standards, frameworks, or technical problems.

If a team has a well balanced group of senior, mid-level, and junior engineers, they can probably operate effectively in a moderate-sized team. By comparison, a team of all senor engineers, say on an infrastructure project, might be able to accommodate twice as many individuals because they should require less communication items and be much less distracted with mundane engineering tasks.

Base level of managerial responsibilities include ensuring the following:

* Engineers are productive on value-adding projects.
* Administrative tasks take place.
* Managers are current on the status of projects and problems.
* one-on-one weekly meeting with engineers.
* So3metimes: coding of features
* Coordinating or conducting code reviews
* Establishing and ensuring adherence to standards, mentoring, praising, and performance reviews. The more of these tasks that must be handled by the individual managers, the smaller the team should be.

Speaking frequently with team members is critical to be an effective manager and leader.

Need of the business: Business owners and product managers, in general, want to grow revenue, fend off competitors, and increase their customer bases. To do so they often need more and increasingly complex functionality. 

One of the main problems with keeping the team size small id that large projects require many more iterations or more time in development. Result: projects take longer to get delivered to the customer.

Another problem is that increasing the number of engineers on staff requires increasing the number of support personnel, including managers. Engineering managers may take offense at being called support personnel, but in reality that is what management should be -> The larger the teams, the fewer the managers per engineer are required.

**There is a limit to the amount a project can be subdivided to expedite delivery** Even then, the larger the team size, the faster projects can be delivered and the larger the projects that can be undertaken.

#### Warning signs.

Factors that signs that the team size is incorrect: 

* Poor communication: engineering missing meetings, unresponsiveness to emails, missed specification changes, multiple people asking the same question.
* Lowered productivity: If the manager, architect, and senior engineers do not have enough time to spend with the junior engineers, these newest team members will not produce as many features as quickly. Or, Senior engineers may be too busy answering questions from too many junior engineers to get their own work done, thereby lowering their productivity. **Note: Engineers by nature are overly optimistic in terms of what they can accomplish**
* Poor morale: this could be the consequence of the first two. Disgruntlement serves to indicate that something is wrong. Poor morale can be demonstrated by a variety of behaviors, such as showing up late for work, spending more time in the game room, arguing more in meetings, and pushing back more than usual on executive-level decisions.  _As an engineer, when you feel unsupported, left out of communication loop, or unable to succeed in your tasks, that state weighs heavily on you_. **When an engineer realizes that he cannot solve a problem, he falls into despair** 

All indicators that the teams has grown too large.

Conversely, if the team is too small, indicators to look for include disgruntled business partners, micromanaging managers, and overworked team members.

Signs:
* Business partners such as product managers, business development, etc. spend more time around the manager complaining that they need more products delivered. A team that is too small is just unable to deliver sizeable features quickly. Alternatively, instead of complaining directly to the engineer or technology leadership, disgruntled business leaders might focus their energy in a more positive manner by supporting budget requests for more engineers to be hired.
* Trend towards micromanaging: Perhaps the manager;s team is too small and she's keeping busy by hovering over the team members, second-guessing their decisions, and asking for status updates about the request for a status update. This is the perfect opportunity to assign the manager some other tasks that will serve the organization.
* Overworked team members: Most teams are extremely motivated by the products they are working on and believe in the mission of the company. If team members start to leave increasingly late each evening, or consistently work on weekends, you might want to investigate whether the particular team includes enough engineers. _take notice of the hours and days spent working on tasks and determine a corrective action early._

Ignoring the symptoms summarized can have disastrous consequences.

#### Growing or splitting teams

Difficult task: split a team when it becomes too large. Factors must be taken into account when undergoing this organizational surgery.

Subdividing a team include how to split the code base, who will be the new manager, what level of involvement will individual team members have -> the relationship with the business partners will change.

(1) Concentrate on the code or the work: split the team as well as the code base into failure domains -- domains that limit the impact of failures by isolating services from one another. The code that used to be owned by and assigned to a single team needs to be split between two or more teams. Possible solution: subdivide the serivces into two or more groups: one group handling account creation and login, the other group handling billing and reporting services. In the case of any changes of ownership, etc. keeping everyone aware of the change will be key to ensure proper ownership and understanding.

(2) Mew manager: Opportunity to hire someone new from the outside or to promote someone internally into the position. An external hire brings new ideas and experiences, whereas an internal hire provides a manager who is familiar with all the team members as well as the processes. **This is a decision that you do not ant to make lightly and might want to ponder for a long time**. Taking too much time to identify a manager can cause just as many problems. The stress of the unknown can damp the employee morale and cause unrest. -> Make a timely decision; if that involves bringing in external candidates, do so as openly and quickly as possible.

(3) How the relationship with the business will be affected.A discussion with all the affected leaders should take place before a decision is reached on splitting the team. Perhaps all counterparts will split simultaneously, or perhaps individuals will be reassigned to interact more directly along team lines. Most important consideration is that an open discussion should take place beyond the engineering and technology team.

**Optimal team-size checklist**

1. Determine the experience level of your managers
2. Calculate each engineer's tenure at the company
3. Look up or ask each engineering how long he or she has been in the industry.
4. Estimate the total effort for managerial responsibilities
 a. Survey your managersto determine how much time they spend on tasks.
 b. Make a list of the core managerial responsibilities that you expect managers to accomplish.
5. Look for signs of disgruntled business partners and managers who are bored to indicate teams that are too small.
6. Look for losses in productivity, poor communication, and degrading morale to indicate teams that are too large.

_Splitting teams_

1. Determine how to separate the code base: Split services; Divide base classes and services as evenly as possible with only one owner.
2. Determine who will be the new manager: Consider internal versus external candidates; Set an aggressive timeline for making the decision and stick to it.
3. Analyze your team's interactions with other teams or departments: Discuss the planned split with other department heads; Coordinate your team's plit with other teams to ensure a smoother transition; Use joint announcements for all departments to help explain all of the changes simultaneously.

### Organizational structure

Organizational structure refers to the actual layout or how teams relate to each other within an organization. -> separation of employees into departments, divisions, and teams as well as the management hierarchy that id used for command and control of the forces.

Two basic structures have been in use throughout the years - functional and matrix -- and a new structure has recently come into favor: Agile. **You can create a hybrid that best meets the needs of your company**

#### Functional Organizational

Organizational structure is the original structure upon which armies and industries were based. SILO APPROACH because each group of people was separated from other groups just as grain or corn would be separated into silos based on the type or grade of crop. 

Technology organizations: functional structure separate departments to house engineering, QA, operations, project management, and so forth. Each group has a department head such as a VP of engineering, and a structure within each department that is homogeneous in terms of responsibilities. -> consistent in that engineering managers report to other engineering managers, and QA managers report into other QA managers.

Benefits: 

* Managers almost always rise through the ranks
* little need to spend time explaining to bosses the more arcane or technical aspects of the job
* The entire organization is built along the lines of specificity
* simplicity of responsibilities ease of task assignment
* Greater adherence to standards
* Everyone, even the newest members, can quickly grasp who is in charge of which team or phase of a project.
* Standards can be established, decreed, agreed upon, and enforced fairly easily.

Problems:

* **Lack of simple project owner and poor cross-functional communication.**
* Projects almost never reside strictly within the purview of a single functional team.
* Simple features quest must have a specification drafted by the product owner, design and coding performed by the engineers, testing performed by the qa team, and deployment by the operations engineers.
* Responsibility for all aspects of the project does not reside with any one person in the management hierarchy until you reach the head of technology, who has responsibility over the product managers, engineering, QA, and operations staff. This is exhacerbated when product doesn't report to the cTO.
* In this setting when problems arise in the projects, it is not uncommon for each functional owner to place the blame for delays or cost overruns on other departments. communication can be surprisingly difficult across departments. -> writing a 20-page test specification leads to much more bourdersome communication than one-on-one conversation between the development engineer and the testing engineer.
* Conflict between teams: "this team didn't delviver something on time". "That other team delivered the wrong thing." common refrains heard when functionally organized teams attempt to work toghether. -> rarelyy there is appreciation of each functional team;s challenges or contributions. For an engineer, both self-identity and social identity are tied in part to being seen as belonging to the tribe of engineers. Engineers want to belong and be accepted by our peers. Others who are different are often seen as outsiders, not trusted, and sometimes the target of open hostility.

#### Conflict

Good and bad forms of conflict. 

Good conflict: **cognitive conflict** healthy debate that teams get into regarding what should be or why something should be done; it involves a wide range of perspectives and experiences. Helps teams open up the range of possibilities for action. Brainstorming sessions and properly run postmortems are examples of controlled cognitive conflict intended to generate a superior set of alternatives and actions.
 * Emotionally and socially intelligent leaders also may help create positive cognitive conflict within teams. Unfortunately, if conflict is left unresolved, it can escalate to affective conflict.

Bad conflict: **affective conflict** role based and often involves how to do something or who should be doing something. Results in physical and organizational trauma. Physically, it can leave us drained, because the sympathetic nervous system (the same system involved in the flight-or-fight syndrome, which is kicked off by the hypothalamus) releases stress and hormones such as costisol, epinephrine, and norepinephrine. 

Affective conflict leaves us feeling exhausted. Organizationally, teams experiencing this type of conflict fight over ownership and approaches. Organizations become fractured, and scholarly reserach shows that the result is a limiting of our ptions from a tactical and strategic perspective. The fighting closes our minds to options, meaning our results may potentially be suboptimal.

Creating an open, caring, and respectful culture, we can both maximize cognitive conflict and minimize affective conflict. By hiring a diverse group of people with complementary skills and perspectives, we can minimize groupthink, maximize strategic options, and encourage our organizations to grow quickly.

#### Matrix organization

The principal concept in a matrix organization is the two dimensions of the hierarchy. The matrix includes at least two dimensions of management structure, whereby each team member may have two or more bosses. Each of these bosses may have a different management responsibilities. 

For example, the traditional functional organization can be augmented with a project management team on the side. Project management within the Project Management Organization (PMO) align with members of the others teams, these constitute a project team. In larger and more complex matrix organizations, many members of each tema can belong to project teams.

This structure alleviates the need to trudge thorugh layers of management in search of the right person.

Athlete analogy: Golfer wants to get better, he surrounds himself with other golfers, and perhaps even a golf instructor, and practices the game of golf. But, to truly excel, athletes must cross-train. 

It mitigates the problem of ownership and coomunication, but introduces the problem of multiple bosses and distraction from a person's primary discipline. Reporting to multiple people causes stressors because of different direction given by each boss. Also, project team requires overhead, as does any team, in the form ot meetings and email communications. This overhead does not replace the team meetings that the engineer must attend for her engineering manager but rather takes more time away from her primary responsibility of coding. The matrix structure introduces new problems.

#### Agile organization

"The best architecture, requirements, and designs emerge from self-organizing teams"

-> a new organization structure that is not based on roles, but rather focused on satisfying the customer.

People develop technology and, therefore, people are important to the process. A truly scalable system requires the alignment of architecture, organization, and process.

An agile organization creates teams that are completely autonomous and self-contained. These teams own a service throughout the entire life cycle - from inception, to development, to support of the service in production. Directors or VPs of cross-functional, Agile teams have replaced the typical managerial role such as VP of Engineering.

#### Theory or innovation

Innovation -> value-added output of a team. 

"Which factors help teams increase their innovation?"

Cognitive conflict brings diverse perspectives and experiences together. Brainstorming sessions are often seen as examples of cognitive conflict, whereby teams attempt to gather a set of alternatives superior to what the team members could arrive at in isolation. In a Brainstorming session, not everyone may agree, byt ideas were exchanged in a respective manner such that roadblocks to solutions were raised and ways around them discussed. This collaboration resulted in creative and innovative ideas that likely no one would have generated on their own.

Destructive conflict is role based and revolves around the questions of "who" and "how" a task should be done. 

Diversity in background helps the discussion on in a brainstorming session. 
**Experiential diversity can increase both affective and cognitive conflict.** Sometimes people with different backgrounds tend to butt heads because they approach problems or opportunities from such a different perspectives.

Diversity of experience also can promote diversity of thoughts, leading to ideas and solutions that go far beyond what a single person could ever achieve. Thus experiential diversity increases both affective and cognitive conflict. The key for us leaders attempting to increase out teams' innovation is to minimize how experiential diversity impacts the affective component and to maximize how it impacts the cognitive aspects.

**Network diversity**, which is a measure to what extent individuals on a team have different personal or professional networks also influences innovation. Teams with diverse networks are better able to identify these potential roadblocks or problems early in the project.

Teams with the most diverse networks are better prepared to find resources outside of their teams to circumvent those obstacles. 

**Sense of empowerment** also positively influences innovation. If a team feels empowered to achieve a goal, it is much more likely to achieve it. **Decreasing empowerment is intended to decrease a candidate's motivation to complete a task... military example**. When individuals or teams believe they are empowered with the resources they need to accomplish something, the innovation increases.

Factor to consider: organizational boundaries, which simply means individuals are on different teams. Between all teams are boundaries that separate them. Some boundaries are narrow, such as those between similar teams, whicle others are uite large, such as those found between very different teams.

Organizational boundaries, across which collaboration must happen, increase affective conflict. The more organizational boundaries that a team must cross to coordinate with others for the accomplishment of a goal, the less innovation the team will demonstrate.

Agile organizations: break dwon the organizational boundaries that functional organizations struggle with and they empower teams, eliminating the problems that matrix organizations face.

Benefits:

* Increased innovation produced by the team, measured in terms of faster time to market with features, greates quality of the product, and higher availability. Increased innovation is driven by the improvement in factos such as conflict, empowerment, and organizational boundaries.

-> When teams align themselves according to services, are autonomous, and have cross-functional composition, the result is a significant decrease in affective conflict. The team members have shared goals and no longer need to argue about who is responsible or who should perform certain tasks. Wins or loses toghether. Everyone is responsible for ensuring the service they provide meets the business goals.

Disadvantages:

* Loss of some traditional roles, such as "VP of engineering". VP of engineering in practice will be the engineering chapter leader or will lead cross-functional agile teams. 
* For it to work as intended, teams need to be aligned to the user-facing services in the architecture. When agile teams overlap in terms of ownership or responsibility of code base, the teams cannot act autonomously.

**Platform teams**: Often these teams work like an open source model, providing libraries or services to other Agile teams.

One outcome people often believe is a disadvantage of the Agile Organization is having software developers, DevOps, QA, and possibly even product managers on call for production issues with services. This is actually a benefit of the organizational structure, because it provides a feedback loop to the team. They will fix issues for the long term. The lessons might be painful in the short term, but they are a game change in the long run.


**Spotify**

Tribes, Squads, Chapters, and Guilds. self-organizing team and decide their own way of working — some use scrum spritns, some use kanban, some use a mix of these approaches. Each squad has a long-term mission based on a service, which the team supports.

Squads have a dedicated product owner who prioritizes the work. Also, they have an agile coach who helps them identify impediments and encourages them to continuously improve their process. 

A tribe is a collection of squads that work in a related area. It can be seen as the "incubator" for the squad mini-startups. Tribes enjoy a fair degree of freedom and autonomy. Each tribe has a tribe lead, who is responsible for providing the best possible habitat for the squads within that tribe. Tribes include fewer than 100 people in total.

A chapter comprises a small group of people having similar skills and working within the same general competency area, within the same tribe. They meet regularly to discuss the area of expertise and specific challenges. Chapter lead serves as the line manager for the chapter members, with all the traditional responsibilities. 

A guild is a more organic and wide-reaching "community of interest"

### In summary

* Organizational structure can either hinder or help a team's ability to produce and support scalable applications.
* Team size and team structure are the two key attributes with regard to organizations.
* Teams that are too small do not provide enough capacity to accomplish the priorities of the business.
* Teams that are too large can cause a loss of productivity and degrade morale. 
* The two traditional organizational structures provide benefits such as commonality of management and peers, simplicity of responsibilities, easu of task assignment, and greater adherence to standards.
* Matrix organizational structures provide benefits suchj as project ownership and improved cross-team communication.
* Agile Organization structures, especially those aligned to services and architecture, rpvoide increased innovation as measured by faster time to market, higher-quality functionality, and higher availability of services.

