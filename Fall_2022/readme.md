# Fall 2022
# Student Projects
Students will work on a student project through the semester to provide a real world example of the open source and engineering practices from class. 
Student projects have been developed by a set of mentors from a number real world open source licensed projects. 
Students will choose a project from the list below and apply for it by sending email to the instructor. 

## Open Source Student Projects 
1. [PASS Student Projects](https://github.com/jhu-ospo-courses/JHU-EN.601.270/tree/main/Fall_2022#pass-projects): PASS is the [Public Access Submission System](https://pass.jhu.edu/), a platform to assist researchers in complying with the access policies of their funders and institutions (e.g. NASA, CDC, NIH). While many federal agencies have policies that require research results to be made publicly accessible, the requirements to comply with these vary greatly from one agency to another. These heterogeneous processes for compliance have become burdensome for researchers and their institutions. For research that is funded by multiple agencies, it can be especially complicated to ensure compliance with each funder’s access policy.
1. [PowerShell Student Projects](https://github.com/jhu-ospo-courses/JHU-EN.601.270/tree/main/Fall_2022#microsoft-powershell-projects): Microsoft [PowerShell Core](https://github.com/PowerShell/PowerShell) is a cross-platform (Windows, Linux, and macOS) automation and configuration tool/framework that works well with your existing tools and is optimized for dealing with structured data (e.g. JSON, CSV, XML, etc.), REST APIs, and object models. It includes a command-line shell, an associated scripting language and a framework for processing cmdlets.
1. [Lutece Student Projects](https://github.com/jhu-ospo-courses/JHU-EN.601.270/tree/main/Fall_2022#lutece-projects): [Lutece](https://lutece-platform.github.io/) is a powerful Java™ based Content Management Framework developed by the [City of Paris](https://lutece.paris.fr/lutece/), and adopted in many places (including the St. Francis Neighborhood Center in Baltimore). 



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
### Lutece project #1: [New plugin development] Similar Availabilities<br>
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

### Lutece project #2: [New plugin development] Sheperd <br>
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

### Lutece project #3: [New plugin development] New resource management system<br>
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

### Lutece project #4: [Plugin contribution] Resource management system module to use within the appointment plugin.<br>
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

### Lutece project #5: [New module development] Appointment queuing management system<br>
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

## enarx Projects
### enarx #1: Benchmarking of WebAssembly/WASI <br>
**Description:** 
WebAssembly/WASI support varies widely across different programming languages. The goal is to create a testing framework that will automatically generate a matrix showing information like I/O support, socket support, file size, execution time, etc. This framework will run code samples from our Codex repository (https://github.com/enarx/codex/).</br>
</br>
**Language:** Bash </br>
**Skills/Background:** GitHub Actions </br> 
**Mentor:** Roman </br>
**Difficulty:** Medium/Hard </br>
<br>
### enarx #2: Secure notes inside Enarx Keep <br>
**Description:** 
Develop a web-based in-memory private text sharing application. Once users connect, they are asked for authentication via an OpenID Connect/OAuth2 provider and have access to either create a new note or read an existing one. </br>
MVP: notes are private and can only be read by the creator.<br>
Stretch goal: sharing notes with a list of users (identified via OIDC subject ID)<br>
Example: https://www.pastebin.com, https://etherpad.org/, https://pad.riseup.net/<br>
</br>
**Language:** Any supported language. </br>
**Skills/Background:** Web development/frameworks </br> 
**Mentor:** Richard, Roman </br>
**Difficulty:** Easy/Medium </br>
<br>
### enarx #3:  Chat app in Enarx Keep <br>
**Description:** 
Develop a chat client using a simple custom protocol running in Enarx. The project can be done in a programming language of your choice and a reference implementation in Rust along with a common Web interface will be provided.
<br>
One of the main case studies for Confidential Computing is the Signal messaging application, which offers end-to-end encryption using Intel SGX. A chat app in Enarx would be cross-platform.
<br>

MVP: Terminal chat client
<br>
Stretch goal: Connect the client to a provided Web Interface </br>
</br>
**Skills/Background:** Networking </br> 
**Mentor:** Richard, Roman </br>
**Difficulty:** Medium/Hard </br>

3.1 Chat app in Rust
<br>
3.2 Chat app in C
<br>
3.3 Chat app in C++

<br>
<br>

## Template: 
### project #: Title
**Description:** 
stuff </br>
**Additional information:** </br>
**Expected outcomes:** </br>
**Language:** </br>
**Skills/Background:** </br> 
**Mentor:** </br>
**Difficulty:** Easy/Medium/Hard </br>
