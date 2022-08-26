# Fall 2022
# Student Projects
Students will work on a student project through the semester to provide a real world example of the open source and engineering practices from class. 
Student projects have been developed by a set of mentors from a number real world open source licensed projects. 
Students will choose a project from the list below and apply for it by sending email to the instructor. 

## Open Source Student Projects 
1. [PASS Student Projects](https://github.com/jhu-ospo-courses/JHU-EN.601.270/tree/main/Fall_2022#pass-projects): PASS is the [Public Access Submission System](https://pass.jhu.edu/), a platform to assist researchers in complying with the access policies of their funders and institutions (e.g. NASA, CDC, NIH). While many federal agencies have policies that require research results to be made publicly accessible, the requirements to comply with these vary greatly from one agency to another. These heterogeneous processes for compliance have become burdensome for researchers and their institutions. For research that is funded by multiple agencies, it can be especially complicated to ensure compliance with each funder’s access policy.
2. [PowerShell Student Projects](https://github.com/jhu-ospo-courses/JHU-EN.601.270/tree/main/Fall_2022#microsoft-powershell-projects): Microsoft [PowerShell Core](https://github.com/PowerShell/PowerShell) is a cross-platform (Windows, Linux, and macOS) automation and configuration tool/framework that works well with your existing tools and is optimized for dealing with structured data (e.g. JSON, CSV, XML, etc.), REST APIs, and object models. It includes a command-line shell, an associated scripting language and a framework for processing cmdlets.
3. [Lutece Student Projects](https://github.com/jhu-ospo-courses/JHU-EN.601.270/tree/main/Fall_2022#lutece-projects): [Lutece](https://lutece-platform.github.io/) is a powerful Java™ based Content Management Framework developed by the [City of Paris](https://lutece.paris.fr/lutece/), and adopted in many places (including the St. Francis Neighborhood Center in Baltimore).
4. [PatternFly Student Projects](#patternfly-projects): [PatternFly](https://www.patternfly.org) is an open source design system built to drive consistency and unify teams, and is used broadly by many open source products from [Red Hat](https://www.redhat.com). From documentation and components to code examples and tutorials, PatternFly is a place where design and development can thrive. We’re on a mission to help teams build consistent, accessible, and scalable enterprise product experiences—the open source way.


## PASS Projects
### PASS #1: Port manuscript download web service from Go to Java. <br>
**Description:** 
This is a small service with a REST API written in Go. It should be completely rewritten as a Java Maven module such that 
the Java version can be a drop in replacement. There also must be unit testing, integration testing, and a Docker container to run the service. </br>
</br>
**Language:** Go, Java </br>
**Skills/Background:** Web Services, Maven, Docker </br> 
**Expected Outcome:** Functioning download service implemented in Java <br>
**Mentor:** PASS team </br>
**Difficulty:** Easy </br>
<br>
### PASS #2: Port metadata schema web service from Go to Java. <br>
**Description:** 
This is a small service with a REST API written in Go. It should be completely rewritten as a Java Maven module such that the Java version can be a drop in replacement. There also must be unit testing, integration testing, and a Docker container to run the service. </br>
</br>
**Language:** Go, Java </br>
**Skills/Background:** Web Services, Maven, Docker </br> 
**Expected Outcome:** unctional schema service implemented in Java <br>
**Mentor:** PASS team </br>
**Difficulty:** Medium </br>
<br>
### PASS #3: Port policy web service from Go to Java. <br>
**Description:** 
This is a small service with a REST API written in Go. It should be completely rewritten as a Java Maven module such that the Java version can be a drop in replacement. There also must be unit testing, integration testing, and a Docker container to run the service. </br>
</br>
**Language:** Go, Java </br>
**Skills/Background:** Web Services, Maven, Docker </br> 
**Expected Outcome:** Functioning policy service implemented in Java <br>
**Mentor:** PASS team </br>
**Difficulty:** Medium </br>
<br>
### PASS #4: Create an acceptance testing module for the UI and import existing mocked tests. <br>
**Description:** 
TestCafe should be used as the framework. Existing tests which have mocked interactions will be used as the initial set of acceptance tests. </br>
</br>
**Language:** Javascript </br>
**Skills/Background:** Node.js, HTML </br> 
**Expected Outcome:** Functioning test suite using imported mocks <br>
**Mentor:** PASS team </br>
**Difficulty:** Medium </br>
<br>


## Microsoft Powershell Projects
### Microsoft Powershell #1: ...

## Lutece Projects
### Lutece project #1
### [New plugin development] Similar Availabilities
**Description:** 
A frequent request we have is for the development of a functionality that allows to find common availabilities in order to 
arrange a meeting time. In a similar way to doodle, the application must allow in the back office to set :
- date ranges on which participants define the time slots where they are available
- time slots
- A list of participants to send the invitation to
- A range of publication dates
- an option to be notified at each contribution / when all participants have filled in their availability
- Match the contributions of all to extract a synthesis (common time slots for all, or those with the most participants)
- ... (any ideas are welcome)

In front-office :
- The login is mandatory to access the functionality
- participants can easily (as user-friendly as possible) enter their availability
- They must be able to modify their contributions during the publication period, or as long as everyone has not responded, 
or as the owner/admin hasn't stopped the campain
- (any ideas are welcome)<br>

</br>
Additional information:<br>
Expected outcomes: <br>
Language: <br>
Skills/Background: <br>
Mentor: <br>
Difficulty: Level 2/5 <br>

### Lutece project #2 <br> 
### Title: [New plugin development] Sheperd <br>
**Description:** 
To improve the distribution and use of lutece in a broad way, we are developing a set of functionalities that will allow to quickly 
learn how to use the business bricks.

We want to set up a wizard that allows the user (back office or front office) to understand how to use the interface. 
Upon a new connection (identified thanks to the cookies), the wizard will automatically launch and suggest to the user to follow a 
guide explaining each element of the page and how to relaunch it once closed. Ideally present on each page, a button allows to launch the dedicated scenario.

Pre-requisite: use a library like sheperdjs, or compatible with our BSD license, e.g. Apache commons, GPL > 3, MIT...)

We would start on the Lutece core project, to help the understanding of RBAC for example, it could then be extended to the plugins 
integrated in the site.

A static example is available and can be shown/run, but needs a better integration and an way to edit the scenarios in the back-office 
and link them to the pages where they need to be accessible.<br>
</br>
**Additional information:** 
</br>
**Expected outcomes:** </br>
**Language:** </br>
**Skills/Background:** </br> 
**Mentor:** </br>
**Difficulty:** Level 2/5 </br>

### Lutece project #3<br>
### Title: [New plugin development] New resource management system<br>
**Description:** 
A new plugin that manages items/resources would be very useful to connect to other plugins.
It would define ressource types along with parameters (duration, pre-reqs, documents – editable fields 
based on the generic-attributes plugin). It would also be indexed and available through SolR (already existing plugin). 
If possible, add a front office page for users to browse through resources and use a filter-based and facets-based search.

It would allow people to either use the resources or borrow them on a specific time range. It would be as generic as possible 
(items, rooms, musical instruments…) and it would be a plus if the user could combine resources (looking for an available trumpet 
and a rehearsal room between Tuesday and Thursday for half a day).</br>

**Additional information:** </br>
**Expected outcomes:** </br>
**Language:** </br>
**Skills/Background:** </br> 
**Mentor:** </br>
**Difficulty:** Level: 3/5 for the management system in Back Office - 4/5 with indexation + front office </br>

### Lutece project #4<br>
### Title: [Plugin contribution] Resource management system module to use within the appointment plugin.<br>
**Description:** 
A Lutece module is considered as a plugins plugin. Plugins bring features to Lutece websites. Modules connect plugins. For example, the appointment plugin features all that is needed to set agendas, availabilities and so on. The workflow plugin brings automation and configurable actions when a resource (request, appointment…) reaches new states. A module that connects the appointment plugin with the workflow plugin (and called module-appointment-workflow) brings all the appointment specificities into the workflow so that we can use business-related functions when appointments switch states.

Currently, such a module exists linking the resource plugin to the appointment plugin. It helps to associate a resource (equipment, staff…) with an appointment, but it can only be done manually : an admin choses a resource from a list and assigns it to the appointment so it is not longer available in the timeslot. The module needs to be upgraded so that this action can be done automatically, according to a few settings :

- Pick randomly from the list
- Choose an item so that it leverages the load of all, or on the contrary the most used so the others don’t get worn out
-  …
Handle the case if no resources are available (notification to the admin, etc.)<br>

**Additional information:** </br>
**Expected outcomes:** </br>
**Language:** </br>
**Skills/Background:** </br> 
**Mentor:** </br>
**Difficulty:** Level: 3/5 starting from a fork - 4/5 otherwise </br>

### Lutece project #5<br>
### Title: [New module development] Appointment queuing management system<br>
**Description:** 
This feature is highly requested by business units across the City. Since the appointment plugin is used to display 
availabilities for more than 400 services, some of them have very high demand. That means there are a few availabilities 
and users hardly find any. In a first version, we would love to provide them the possibility to register to a list that 
would be notified every time there are new availabilities – on a date range, or time range - due to cancelations or new 
timeslots added (any ideas to be as user-friendly as possible are welcome).</br>
<br>
**Additional information:** </br>
**Expected outcomes:** </br>
**Language:** </br>
**Skills/Background:** </br> 
**Mentor:** </br>
**Difficulty:** Level: 5/5 </br>
<br>

## PatternFly projects

### PatternFly project #1: Convert interactive component examples from Javascript to Typescript

**Description:**
PatternFly examples provide interactive working code snippets which illustrate different use cases to consumers and allow them to try out various interactions.  These examples were originally written in Javascript + React, but are being converted to Typescript + React to provide increased guardrails around their usage and better match the current technologies of our consumers.  Each PatternFly component typically contains several exaamples, so this project allows a student to ramp up in complexity while offering a quick path to making pull request contributions and see their work reflected on our live website.
</br>

**Additional information:** This work consists of many smaller issues contained within one large epic.  All mentors and the greater team have experience with this workflow, and existing completed work serves as a template to help students ramp up quickly.  Students will work into PatternFly's 3-week sprint schedule.</br>
**Expected outcomes:** Students will gain confidence in Typescript, be able to submit multiple pull requests building towards this goal, and see completed work reflected live to our community on the PatternFly website.</br>
**Language:** Javascript, Typescript, React</br>
**Skills/Background:** </br>
**Mentors:** Austin & Eric</br>
**Difficulty:** Medium </br>

### PatternFly project #2: Update component unit tests to meet new standards with React Testing Library

**Description:**
PatternFly is used by individual consumers and massive corporate software alike, and as such must maintain a focus on consistency and reliability even while releasing every three weeks.  To this end the PatternFly team implements several different methods for testing code to ensure no breaking changes are introduced - unit tests, snapshot tests, integration tests, accessibility testing, manual end-to-end testing, and more.  The team's goal is to reimplement unit tests with React Testing Library, which will be enable support for React 18 while allowing the team to ensure that tests are accurately covering all required test cases and not providing a false sense of security.</br>

**Additional information:**  This work consists of many smaller issues contained within one large epic.  The PatternFly team has recently ramped up on React Testing Library ([documentation captured here](https://github.com/patternfly/patternfly-react/wiki/React-Testing-Library-Basics,-Best-Practices,-and-Guidelines)) and are happy to bring a student up to speed on this technology as well, so no React Testing Library prior experience is required.  Existing completed work serves as templates that students can reference,   Students will work into PatternFly's 3-week sprint schedule.</br>
**Expected outcomes:** Students will gain understanding of & appreciation for testing code, specifically with React Testing Library.  They will be able to contribute multiple smaller pull requests towards this larger epic, and their work will help ensure the PatternFly code base remains stable moving forward.</br>
**Language:** React</br>
**Skills/Background:** </br>
**Mentor:** Austin (primary), Eric</br>
**Difficulty:** Medium</br>

### PatternFly project #3: Improve PatternFly.org website's accessibility

**Description:**
PatternFly prides itself on putting a focus on accessibility into every decision - the design system should cater to all users, regardless of their specific abilities.  In addition to the code the team ships and is consumed by users, the documentation website which not only provides general information about PatternFly but also interactive examples and demos should maintain a focus on accessibility.  This project is aimed to resolve many accessibility bugs identified across the PatternFly website, which can be related to specific component HTML/Handlebars or React/Typescript code examples, custom code used specifically to build out the website, or other combinations of issues.  Errors have been pre-identified by the React team, and this project consists of a number of smaller code contributions that can be split up across multiple pull requests.</br>

**Additional information:**  This work consists of many smaller issues contained within one large epic.  Previous accessibility work is not required to be successful.  Existing completed work serves as templates that students can reference.  Students will work into PatternFly's 3-week sprint schedule.</br>
**Expected outcomes:** Students will gain understanding of & appreciation for accessible web experiences, and learn about automated accessibility testing through aXe, keyboard interaction, and screen readers.  They will be able to contribute multiple smaller pull requests towards this larger epic, and their work will have immediate impacts on PatternFly's website.</br>
**Language:** React, HTML, Handlebars</br>
**Skills/Background:** </br>
**Mentor:** Eric (primary), Austin</br>
**Difficulty:** Medium</br>


Template: 
### project #: Title
**Description:** 
stuff </br>
**Additional information:** </br>
**Expected outcomes:** </br>
**Language:** </br>
**Skills/Background:** </br> 
**Mentor:** </br>
**Difficulty:** Easy/Medium/Hard </br>
