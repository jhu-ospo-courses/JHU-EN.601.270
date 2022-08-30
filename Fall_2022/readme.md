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
5. [enarx Student Projects](#enarx-projects): The [enarx project](https://enarx.dev/) is an open source framework for running applications in TEEs (Trusted Execution Environments). It's part of the Confidential Computing Consortium from the Linux Foundation. It provides a WebAssembly runtime which uses TEEs, allowing developers to deploy secure applications using a variety of languages, such as: Rust, C/C++, C#, Go, and more. It is CPU-architecture independent, letting developers deploy the same application code transparently across multiple targets and architectures


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

### PowerShell Language Projects
#### Description : PowerShell is a task automation and configuration management program from Microsoft, consisting of a command-line shell and the associated scripting language. 

### PowerShell #1: Feature Request - ConvertTo-Html should auto create hyperlinks
**Description:** 
There are many times where I've had to go manually craft an `<a href="....` as a new property where the existing string property already had a valid URL in it, just so ConvertTo-Html would generate a hyperlink.  </br>
**Additional information:** https://github.com/PowerShell/PowerShell/issues/11458 </br>
**Language:** C#/PowerShell </br>
**Mentor:** PowerShell Team </br>
**Difficulty:** Easy </br>

### PowerShell #2: $PSModuleAutoLoadingPreference accepts bogus values
**Description:** 
[About Preference Variables](https://docs.microsoft.com/en-us/powershell/module/microsoft.powershell.core/about/about_preference_variables?view=powershell-7) and [PSModuleAutoLoadingPreference Enum](https://docs.microsoft.com/en-us/dotnet/api/system.management.automation.psmoduleautoloadingpreference?view=pscore-6.2.0) suggest that `$PSModuleAutoLoadingPreference` should be strongly-typed like, for example, `$ErrorActionPreference`.  It does not seem to be strongly-typed, however, and accepts bogus values. </br>
**Additional information:** https://github.com/PowerShell/PowerShell/issues/12037 </br>
**Language:** C#/PowerShell </br>
**Mentor:** PowerShell Team </br>
**Difficulty:** Medium </br>

### PowerShell #3: Add SuppressAnalyzer type alias
**Description:** 
As a script author, I want to _shorten_ the repetitive line required to suppress ScriptAnalyzer rules. </br>
**Additional information:** https://github.com/PowerShell/PowerShell/issues/14784 </br>
**Language:** C#/PowerShell </br>
**Mentor:** PowerShell Team </br>
**Difficulty:** Medium </br>

### PowerShell #4: Output formatting for [System.Reflection.Assembly] instances should show relevant information, not properties only relevant in Windows PowerShell
**Description:** 
The default output formatting for `[System.Reflection.Assembly]` instances shows information that only applies to _Windows PowerShell_ (.NET Framework): </br>
**Additional information:** https://github.com/PowerShell/PowerShell/issues/16020 </br>
**Language:** C#/PowerShell </br>
**Mentor:** PowerShell Team </br>
**Difficulty:** Medium </br>

### PowerShell #5: Remoting over SSH: Multiple issues with the SSHConnection parameter
**Description:** 
The parameter should recognize `~` syntax and look in the users home directory. </br>
**Additional information:** https://github.com/PowerShell/PowerShell/issues/16684 </br>
**Language:** C#/PowerShell </br>
**Skills:** Networking </br>
**Mentor:** PowerShell Team </br>
**Difficulty:** Medium </br>

### PowerShell #6: Add YAML Frontmattter support to ConvertFrom-Markdown
**Description:** 
As a contributor to a Markdown wiki repo, I would like to be able to (cleanly) parse [YAML frontmatter](https://pandoc.org/MANUAL.html#extension-yaml_metadata_block) blocks in PowerShell via `ConvertFrom-Markdown`. </br>
**Additional information:** https://github.com/PowerShell/PowerShell/issues/16857 </br>
**Language:** C#/PowerShell </br>
**Mentor:** PowerShell Team </br>
**Difficulty:** Medium </br>

### PowerShell #7: Getting the SecurityDescriptor from the filesystem provider produces an error on Linux
**Description:** 
The failure of this api gives a poor experience to the user. We should at least produce no error. </br>
**Additional information:** https://github.com/PowerShell/PowerShell/issues/1770 </br>
**Language:** C#/PowerShell </br>
**Skills:** NativeAPI, Security </br>
**Mentor:** PowerShell Team </br>
**Difficulty:** Hard </br>

### PowerShellGet Projects
#### Description: PowerShellGet is a module with commands for discovering, installing, updating and publishing PowerShell artifacts like Modules, DSC Resources, Role Capabilities, and Scripts.

### PowerShell #8: Add -RequiredResource(File) for Save-Module
**Description:** 
There are many circumstances where you want to install modules to somewhere other than the powershell modules folder, for instance if creating the equivalent of a python "virtual environment" for CI builds, or other circumstances where you want a module but don't want to deploy it to the main path. </br>
**Additional information:** https://github.com/PowerShell/PowerShellGet/issues/143 </br>
**Language:** C#/PowerShell </br>
**Mentor:** PowerShell Team </br>
**Difficulty:** Medium </br>

### PowerShell #9: Create `New-RequiredResourceFile` cmdlet
**Description:** 
This cmdlet will create a template file. If the switch -AsPSD1 is used it will create a psd1 file, otherwise it will default to JSON. </br>
**Additional information:** https://github.com/PowerShell/PowerShellGet/issues/587 </br>
**Language:** C#/PowerShell </br>
**Mentor:** PowerShell Team </br>
**Difficulty:** Hard </br>

### PowerShell #10: Uninstall-PSResource should show progress info
**Description:** 
Particularly where there are dependencies, it can take awhile and the user doesn't know what's happening </br>
**Additional information:** https://github.com/PowerShell/PowerShellGet/issues/597 </br>
**Language:** C#/PowerShell </br>
**Mentor:** PowerShell Team </br>
**Difficulty:** Medium </br>

### PowerShell #11: If no package is uninstalled the cmdlet should emit an error
**Description:** 
If no package is uninstalled during a run of `Uninstall-PSResource` the cmdlet should emit a warning so that the user knows no action was completed. The warning can suggest users run `Get-PSResource`. </br>
**Additional information:** https://github.com/PowerShell/PowerShellGet/issues/598 </br>
**Language:** C#/PowerShell </br>
**Mentor:** PowerShell Team </br>
**Difficulty:** Easy </br>

### PowerShell #12: Find-PSResource does not accept pipeline input
**Description:** 
Add support for pipeling input </br>
**Additional information:** https://github.com/PowerShell/PowerShellGet/issues/666 </br>
**Language:** C#/PowerShell </br>
**Mentor:** PowerShell Team </br>
**Difficulty:** Easy </br>

### PowerShell #13: Uninstall-PSResource should have a PassThru parameter
**Description:** 
Uninstall-PSResource should have a PassThru parameter for the caller to get the list of resources uninstalled. </br>
**Additional information:** https://github.com/PowerShell/PowerShellGet/issues/667 </br>
**Language:** C#/PowerShell </br>
**Mentor:** PowerShell Team </br>
**Difficulty:** Easy </br>

### PowerShell #14: Add Set-PSResourceRepository Name parameter wildcard support
**Description:** 
I would like to be able to pass wildcard characters to `Set-PSResourceRepository` name parameter. </br>
**Additional information:** https://github.com/PowerShell/PowerShellGet/issues/671 </br>
**Language:** C#/PowerShell </br>
**Mentor:** PowerShell Team </br>
**Difficulty:** Easy </br>

### PowerShell #15: Publish-PSResource add a PassThru parameter
**Description:** 
As a user I would like `Publish-PSResource` to have a `PassThru` parameter to output a `PSResourceInfo` object with all associated metadata. </br>
**Additional information:** https://github.com/PowerShell/PowerShellGet/issues/718 </br>
**Language:** C#/PowerShell </br>
**Mentor:** PowerShell Team </br>
**Difficulty:** Easy </br>

### PowerShell #16: Update-PSResource with specific resource writes warning and not error
**Description:** 
Currently Update-PSResource Microsoft.PowerShell.SecretStore with a specific resource name and the resource is not installed it will write a warning. This should be an error since the user specifically told the cmdlet to update an individual resource and it was unable to do so. </br>
**Additional information:** https://github.com/PowerShell/PowerShellGet/issues/729 </br>
**Language:** C#/PowerShell </br>
**Mentor:** PowerShell Team </br>
**Difficulty:** Easy </br>

### PowerShell #17: Add PassThru parameter to New-PSScriptFileInfo
**Description:** 
As a script writer I want to be able to use `New-PSScriptFileInfo` to generate a PSScriptInfo comment block, after I have already created a script, without being required to create a temporary file to satisfy the mandatory `FilePath` parameter. </br>
**Additional information:** https://github.com/PowerShell/PowerShellGet/issues/737 </br>
**Language:** C#/PowerShell </br>
**Mentor:** PowerShell Team </br>
**Difficulty:** Easy </br>

### Script Analyzer Projects
#### Description: PSScriptAnalyzer is a static code checker for PowerShell modules and scripts. PSScriptAnalyzer checks the quality of PowerShell code by running a set of rules.

### PowerShell #18: Add Get-ScriptAnalyzerSetting cmdlet to generalize a way of displaying collections of rules
**Description:** 
As a user I want to be able to discover what rules are defined in a PSD1 file, especially those that are included with PSScriptAnalyzer. I would also like to point to any PSD1 file containing rules and get the same output. </br>
**Additional information:** https://github.com/PowerShell/PSScriptAnalyzer/issues/1740 </br>
**Language:** C#/PowerShell </br>
**Mentor:** PowerShell Team </br>
**Difficulty:** Medium </br>

### PowerShell #19: Add a rule to alert `catch [RuntimeException] { ... }`
**Description:** 
See Summary of the new feature </br>
**Additional information:** https://github.com/PowerShell/PSScriptAnalyzer/issues/1744 </br>
**Language:** C#/PowerShell </br>
**Skills:** Language Syntax </br>
**Mentor:** PowerShell Team </br>
**Difficulty:** Medium </br>

- Project 19: 

### PowerShell #20: Setting `$ErrorView` is flagged as a warning: `PSUseDeclaredVarsMoreThanAssignment`
**Description:** 
The rule needs to be altered to exclude this variable as something to warn about </br>
**Additional information:** https://github.com/PowerShell/PSScriptAnalyzer/issues/1749 </br>
**Language:** C#/PowerShell </br>
**Mentor:** PowerShell Team </br>
**Difficulty:** Easy </br>

### Secret Management Projects
#### Description: PowerShell SecretManagement module provides a convenient way for a user to store and retrieve secrets. The secrets are stored in SecretManagement extension vaults. An extension vault is a PowerShell module that has been registered to SecretManagement, and exports five module functions required by SecretManagement. An extension vault can store secrets locally or remotely. Extension vaults are registered to the current logged in user context, and are available only to that user.

### PowerShell #21: [Feature] Provide the version of Extension in Get-SecretVault
**Description:** 
Allow `Get-SecretVault` to include a property for the version of the extension currently loaded to help users and extension developers ensure they have the expected extension version loaded. </br>
**Additional information:** https://github.com/PowerShell/SecretManagement/issues/171 </br>
**Language:** C#/PowerShell </br>
**Mentor:** PowerShell Team </br>
**Difficulty:** Easy </br>

### PowerShell #22: Verbose output for Get-Secret is incorrect
**Description:** 
If a secret does not exist, verbose output still indicates it was able to be retrieved. </br>
**Additional information:** https://github.com/PowerShell/SecretManagement/issues/200 </br>
**Language:** C#/PowerShell </br>
**Skills:** Security
**Mentor:** PowerShell Team </br>
**Difficulty:** Easy </br>

### PowerShell #23: Request - Lock-SecretStore cmdlet
**Description:** 
Create a new cmdlet which enables you to lock access to the secret store </br>
**Additional information:** https://github.com/PowerShell/SecretStore/issues/82 </br>
**Language:** C#/PowerShell </br>
**Skills:** Security
**Mentor:** PowerShell Team </br>
**Difficulty:** Medium </br>

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

## enarx projects

### enarx #1: Benchmarking of WebAssembly/WASI
**Description:** 
WebAssembly/WASI support varies widely across different programming languages. The goal is to create a testing framework that will automatically generate a matrix showing information like I/O support, socket support, file size, execution time, etc. This framework will run code samples from our Codex repository (https://github.com/enarx/codex/). </br>
**Language:** Bash </br>
**Skills/Background:** GitHub Actions </br> 
**Mentor:** Roman </br>
**Difficulty:** Medium/Hard </br>

### enarx #2: Secure notes inside Enarx Keep
**Description:** 
Develop a web-based in-memory private text sharing application. Once users connect, they are asked for authentication via an OpenID Connect/OAuth2 provider and have access to either create a new note or read an existing one. </br>
**MVP:** Notes are private and can only be read by the creator. </br>
**Stretch Goal:** Sharing notes with a list of users (identified via OIDC subject ID) </br>
**Language:** Any supported language </br>
**Skills/Background:** Web development/frameworks </br> 
**Mentor:** Richard, Roman </br>
**Difficulty:** Easy/Medium </br>
**Examples:** https://www.pastebin.com, https://etherpad.org/, https://pad.riseup.net/

### enarx #3: Chat app in Enarx Keep (Multiple Students)
**Description:** 
Develop a chat client using a simple custom protocol running in Enarx. The project can be done in a programming language of your choice and a reference implementation in Rust along with a common Web interface will be provided.
One of the main case studies for Confidential Computing is the Signal messaging application, which offers end-to-end encryption using Intel SGX. A chat app in Enarx would be cross-platform. </br>
* Chat app in Rust
* Chat app in C
* Chat app in C++ </br>
**MVP:** Terminal chat client </br>
**Stretch goal:** Connect the client to a provided Web Interface </br>
**Language:** </br>
**Skills/Background:** Networking </br> 
**Mentor:** Richard, Roman </br>
**Difficulty:** Medium/Hard </br>


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
