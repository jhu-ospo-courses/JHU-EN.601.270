# Student Projects
Students will work on a student project through the semester to provide a real world example of the open source and engineering practices from class. 
Student projects have been developed by a set of mentors from a number real world open source licensed projects. 
Students will choose a project from the list below and apply for it by sending email to the instructor. 

## Open Source Student Projects 
1. [Semester.ly Student Projects](https://github.com/jhu-ospo-courses/JHU-EN.601.270/blob/main/Student%20Projects/readme.md#semesterly-projects): [Semester.ly](https://semester.ly/) is a web platform created by students for students to bring modern technology to the most difficult and archaic parts of higher education. You may well be using it yourself. Semester.ly projects cover a wide range of problems to be solved. 
1. [OpenCRAVAT Student Projects](https://github.com/jhu-ospo-courses/JHU-EN.601.270/blob/main/Student%20Projects/readme.md#opencravat-projects): [OpenCRAVAT](https://opencravat.org/index.html) is a new open source, scalable decision support system to support variant and gene prioritization. It is written in Python and developed in the [Karchin Lab](https://karchinlab.org/) at Johns Hopkins University in collaboration with In Silico Solutions with funding provided by the National Cancer Institute's ITCR program. 
1. [PASS Student Projects](https://github.com/jhu-ospo-courses/JHU-EN.601.270/blob/main/Student%20Projects/readme.md#pass-projects): PASS is the [Public Access Submission System](https://pass.jhu.edu/), a platform to assist researchers in complying with the access policies of their funders and institutions (e.g. NASA, CDC, NIH). While many federal agencies have policies that require research results to be made publicly accessible, the requirements to comply with these vary greatly from one agency to another. These heterogeneous processes for compliance have become burdensome for researchers and their institutions. For research that is funded by multiple agencies, it can be especially complicated to ensure compliance with each funder’s access policy.
1. [PowerShell Student Projects](https://github.com/jhu-ospo-courses/JHU-EN.601.270/blob/main/Student%20Projects/readme.md#microsoft-powershell-projects): Microsoft [PowerShell Core](https://github.com/PowerShell/PowerShell) is a cross-platform (Windows, Linux, and macOS) automation and configuration tool/framework that works well with your existing tools and is optimized for dealing with structured data (e.g. JSON, CSV, XML, etc.), REST APIs, and object models. It includes a command-line shell, an associated scripting language and a framework for processing cmdlets.
1. Lutece Student Projects: [Lutece](https://lutece-platform.github.io/) is a powerful Java™ based Content Management Framework developed by the [City of Paris](https://lutece.paris.fr/lutece/), and adopted in many places (including the St. Francis Neighborhood Center in Baltimore). 

## Semester.ly Projects 
### Semester.ly #1: Revive Advanced Search Feature 
**Description:** 
Our current advanced search feature is broken and often inconvenient for the average user, we need want it to not only be fixed but be greater than its foundational concept. Advanced Search comprises of search by Dept., Area, Level, & Day/Time, but at the moment, there are bugs across all these filters. It needs to be either completely rewritten with a fresh set of eyes or the original system can be built upon and improved. The goal is to not only fix the advanced search feature but truly make it a seamless, more intuitive user experience.  
**Language:**  
**Skills/Background:** Redux, React  
**Mentor:** Sebastian  
**Difficulty:** Easy/Medium  

### Semester.ly #2: New Social Features
**Description:**
Textbook Marketplace, Links to Group chats, Links to new student projects, LinkedIn links, Improved User Profiles (choose profile pictures, adjust personal links, etc.), etc. are all ideas to increase social interactions between students.
At the moment, we have the Facebook integration to use the FB login and see friends in the same classes, but the social features are lacking. We can add many unique social features that don't conflict with typical social media platforms.
The goal is to create a stepping stone for regular social interactions with a variety of new social features (at a minimum 3-5 distinct ideas).  
**Language:**   
**Skills/Background:** None   
**Mentor:** Sebastian   
**Difficulty:** Easy to Hard  

### Semester.ly #3: Semester.ly API
**Description:**
To enhance our partnership with UCredit as well as any other new student projects, we can create an API that simplifies accessing certain features unique to Semester.ly. An API (Application Programming Interface) communicates with an app and gets information in return. Semly can provide a gateway to simplifying course scheduling at a software level for developers interested in quickly integrating specific tools in Semester.ly into their projects or work cycle.
The goal is to create a working API that covers at least 50% of Semly's features.  
**Language:**  
**Skills/Background:** Preferred: Django, Node, REST APIs Required: Basic understanding of REST APIs  
**Mentor:** Sebastian or Ali  
**Difficulty:** Easy to Hard  

### Semester.ly #4: Course Recommendation System
**Description:** 
To ease students' worries about finding the "right" courses, Semly can have a Machine Learning (ML) model to create a course recommendation system. An ML model can be built from our Google Analytics, user surveys, course ratings, and other information to create course recommendations based on each major (or year, etc.). This requires being cautious with basic user information and focusing on developing something that can consistently improve over time with increased user interaction. The goal is to create a foundation for a fully functioning ML model. This must be well-documented and ideally, relatively simple for the future developers to contribute.  
**Language:**  
**Skills/Background:** Required: Python, Thorough understanding of Machine Learning  
**Mentor:** Sebastian or Ali  
**Difficulty:** Hard  

### Semester.ly #5: Course Evaluations API
**Description:**  
Discard previous Course Evaluations modal and create a new API connected with JHU Evaluations. At some point, we integrated Course Evaluations directly integrated with HTML files, but there must be a long-term solution to regularly update course evaluations and populate them across all courses. An API will be the simplest and best way to communicate with Hopkins public course evaluation statistics and allow students to suggest additional comments/reactions.
The goal is to create a new API to integrate course evaluations directly into Semester.ly. There can be a new basic dashboard to view course evaluations in a sleek and accessible format if time permits.  
**Language:**  
**Skills/Background:** Preferred: Basic understanding of APIs, React, Redux, HTML/CSS  
**Mentor:** Ali or Sebastian  
**Difficulty:** Medium to Hard  

## OpenCRAVAT Projects
### OpenCRAVAT #1: Gene-centric annotation of noncoding elements 
**Description:** 
Genes tend to be more well-annotated than noncoding regions. In many cases, a particular gene has evidence for relationship to noncoding elements that is made available by one or more data sources. In this project, we seek to enable users to identify variants within noncoding elements that are relevant to a particular gene (or set of genes).  
**Expected outcomes:** Annotation module, filters  
**Skills/Background:** Python programming, genetics background  
**Mentors:** Kym Pagel, Rick Kim, or Kyle Moad  
**Difficulty:** Medium  

### OpenCRAVAT #2: Gene set analysis 
**Description:**
The are around 20-30,000 genes in the human genome. Previous work has identified several subsets of these genes that are relevant to human conditions.  For example, several thousand genes are relevant to cancer. In this project, we aim to help users query and summarize variants within commonly used gene sets.  
**Expected outcomes:** Annotation modules, filter interface modifications  
**Skills/Background:** Python programming, genetics background  
**Mentors:** Kym Pagel, Rick Kim, or Kyle Moad  
**Difficulty:** Medium  

### OpenCRAVAT #3: Variant Ranking
**Description:**  
There are about 3 million variants in the average human genome, but a small set of these variants are relevant to human health. To make it easier to find these variants, we will create a variant ranking system that identifies variants that are likely benign, have uncertain impact, and are likely pathogenic. Gene-level features would play a strong impact here.  
**Expected outcomes:** Annotation module  
**Skills/Background:** Python programming, biological knowledge  
**Mentor:** Kym Pagel  
**Difficulty:** Easy  

### OpenCRAVAT #4: Advanced visualization widgets for multiple mutations 
**Description:**  
Assessing the distribution of variants in a given genome, gene or noncoding element is strongly benefited by visualization techniques. In this project, we will implement new graphical widgets to show users where variants occur within genes, regions, and genomes.  
**Expected outcomes:** 2-3 visualization widgets  
**Skills/Background:** Python programming, Javascript  
**Mentors:** Rick Kim or Kyle Moad  
**Difficulty:** Medium  

### OpenCRAVAT #5: Connection to Diverse Data Formats
**Description:**
Most users input VCF-formatted data, but these files can quickly become bulky for cohort-level data. Alternative data formats such as Genomic data structure (GDS) files are a more space and memory efficient alternative. In this project, we will build reporter and converter modules to help OpenCRAVAT handle this new data format, among other formats.  
**Expected outcomes:** 2-3 converter modules  
**Skills/Background:** Python programming  
**Mentors:** Kym Pagel or Rick Kim  
**Difficulty:** Medium  

### OpenCRAVAT #6: Efficient Cloud computing 
**Description:**  
Variant annotation through OpenCRAVAT is largely serial. On the cloud, Google BigQuery provides various annotation datasets such that each variant, or set of variants, can be queried simultaneously. In this project, we will edit the existing code of OpenCRAVAT to leverage the BigQuery data to more efficiently annotate variants in cloud environments.  
**Expected outcomes:** Dedicated cloud-computing module  
**Skills/Background:** Python programming, cloud computing expertise  
**Mentor:** Kyle Moad  
**Difficulty:** Medium  

## PASS Projects
### PASS #1: Automatically suggest keywords for PASS submissions  
**Description:** 
Users can optionally describe submitted articles with keywords. The goal would be to automatically suggest keywords based on the text. </br>
**Language:** Javascript, Java</br>
**Skills/Background:** Machine learning, Natural Language Processing, Docker, Web Services</br> 
**Mentor:** Mark</br>
**Difficulty:** Easy to Hard </br>

### PASS #2: Develop a PASS dashboard for super users  
**Description:** 
Administrators like the Vice Provost for Research would like to easily see information such as submission status and compliance. </br>
**Language:** Javascript</br>
**Skills/Background:** Docker, Web services</br> 
**Mentor:** Mark</br>
**Difficulty:** Easy to Hard </br>

### PASS #3: Swap out existing document store  
**Description:** 
PASS uses the Fedora repository to store JSON-LD documents. Switching to a simpler document store might simplify the architecture and improve performance. </br>
**Language:** Java, Javascript </br>
**Skills/Background:** Docker, JSON-LD, Web Services </br> 
**Mentor:** Mark, Derek </br>
**Difficulty:** Easy to Hard </br>

### PASS #4: Update to Elasticsearch 7  
**Description:** 
Currently PASS uses Elasticsearch 6. Upgrading to 7 could open up some new possibilities. </br>
**Language:** Javascript </br>
**Skills/Background:** Docker, Web Services</br> 
**Mentor:** Mark, Derek </br>
**Difficulty:** Easy to Hard </br>

### PASS #5: Create tools to improve management of the document store and index  
**Description:** 
The document store is a Fedora repository which is indexed by Elasticsearch. A [pain point (Issue #149)](https://github.com/OA-PASS/general-issues/issues/149) operating PASS has been ensuring the documents are valid and consistent with the index.  </br>
**Language:** Javascript, Java</br>
**Skills/Background:** Docker, Web services</br> 
**Mentor:** Mark, Bethany</br>
**Difficulty:** Easy to Hard </br>

### PASS #6: PASS Deposit into Islandora System  
**Description:** 
The first part of this is to learn the [PASS deposit service](https://github.com/OA-PASS/deposit-services) well enough to understand the infrastructure for how deposits into DSpace are currently architected.  Then, based on that, document a way and possibly implement how to do something similar for deposits into our new Islandora digital repository system.  </br>
**Language:** Java</br>
**Skills/Background:** Docker / REST API / Some Drupal </br> 
**Mentor:** Bethany </br>
**Difficulty:** Medium/Hard </br>

### PASS #7: Develop Usage Statistics About People Using the Platform While Maintaining Privacy  
**Description:** 
The goal of this project is to develop statistics which would support investigations into how users navigate the site. Tracking a user’s session will give us data about what pages they find useful, and answer questions like, “do users use the dashboards?” This will inform further UI development. </br>
**Language:** </br>
**Skills/Background:** Docker / Web Services </br> 
**Mentor:** Jim, Derek(privacy) </br>
**Difficulty:** Easy/Medium </br>

### PASS #8: Develop Mechanisms to Identify Submission Failures or Incomplete Submissions and Provide Notifications  
**Description:** 
The submission process has many steps, and hence many opportunities for failure. It is important that a submitter knows when a failure occurs so that he or she will not be under the false impression that the submission succeeded. System administrators also need to know the nature of the failure so that the problem can be corrected. Modes of notification may be different for different classes of user and different points of failure.   </br>
**Language:** Java</br>
**Skills/Background:** Docker / Web Services </br> 
**Mentor:** Jim </br>
**Difficulty:** Medium </br>

## Microsoft Powershell Projects
### Microsoft Powershell #1: Fix Set-Location cmdlet’s error message 
**Description:** 
If the Set-Location cmdlet fails due to a permissions error, it writes an error message. This message needs to be more descriptive and indicative of the issue. </br>
**Additional Info:** [https://github.com/PowerShell/PowerShell/issues/15680](https://github.com/PowerShell/PowerShell/issues/15680)  
**Language:** C#</br>
**Skills/Background:** C#, File Systems recommended</br> 
**Mentor:** </br>
**Difficulty:** Medium (students would get experience with delving into the engine providers code base of PowerShell) </br>

### Microsoft Powershell #2: Add .ResolvedTarget property to file system instances  
**Description:** 
Symlinks are usually defined with relative paths and our current FileInfo and DirectoryInfo file system instances have a .Target property which contains the symlink’s path but as it was defined (relative path). We would like to add a property, .ResolvedTarget, which would contain the symlink’s path but resolved to its full (absolute) path. </br>
**Additional Info:** [https://github.com/PowerShell/PowerShell/issues/13366](https://github.com/PowerShell/PowerShell/issues/13366)
**Language:** C#</br>
**Skills/Background:** C#, file systems, APIs recommended</br> 
**Mentor:** </br>
**Difficulty:** Medium </br>

### Microsoft Powershell #3: Correct range on Depth parameter for ConvertTo-Json cmdlet  
**Description:** 
ConvertTo-Json is a PowerShell cmdlet that performs serialization. It takes a Depth parameter, which should only take a maximum value of 100, but currently takes int.MaxValue. Student(s) will need to change this, add tests (via PowerShell scripting) and validation for this scenario. They will also get experience working with PowerShell parameter attributes. </br>
**Additional Info:** [https://github.com/PowerShell/PowerShell/issues/15344](https://github.com/PowerShell/PowerShell/issues/15344)
**Language:** C#</br>
**Skills/Background:** C#, scripting, JSON, testing recommended</br> 
**Mentor:** </br>
**Difficulty:** Intermediate </br>

### Microsoft Powershell #4: Write-Progress cmdlet not rendered when no wait time in between  
**Description:** 
The Write-Progress cmdlet writes progress information to the screen. If you have multiple calls in quick succession, only the first progress message is displayed until some time has elapsed and subsequent progress updates are not provided for some time. Since this is interactive code it may need to also be tested manually. </br>
**Additional Info:** [https://github.com/PowerShell/PowerShell/issues/13005](https://github.com/PowerShell/PowerShell/issues/13005)
**Language:** C#</br>
**Skills/Background:** C#, PowerShell scripting for testing, validation recommended</br> 
**Mentor:** </br>
**Difficulty:** EMedium/Advanced (due to working with test hooks and asynchronous code) </br>

### Microsoft Powershell #5: Replace & with WorkingDirectory parameter where Set-Job called
**Description:** 
The implementation of & background invocation operator should be using the -WorkingDirectory parameter of Start-Job cmdlet rather than relying on $using:pwd as a way to pass the current working directory. We need to replace this in the code referenced in this issue and then write tests to validate. </br>
**Additional Info:** [https://github.com/PowerShell/PowerShell/issues/10515](https://github.com/PowerShell/PowerShell/issues/10515)
**Language:** C#</br>
**Skills/Background:** C#, PowerShell scripting for testing, validation recommended</br> 
**Mentor:** </br>
**Difficulty:** Low (simple fix, but needs validation) </br>

### Microsoft Powershell #6: Add StrictMode parameter to Invoke-Command cmdlet
**Description:** 
The Invoke-Command cmdlet needs to have and support a StrictMode parameter, which PowerShell uses to terminate code that doesn’t follow coding best practices. Currently, the user can add a line in their script which calls the Set-StrictMode cmdlet. By adding this as a parameter to Invoke-Command instead, a user could set this in the $PSDefaultParameterValues variable and have it applied to all their scripts without having to explicitly add the call in each script. </br>
**Additional Info:** [https://github.com/PowerShell/PowerShell/issues/2692](https://github.com/PowerShell/PowerShell/issues/2692) </br>
**Language:** C#</br>
**Skills/Background:** C#, PowerShell scripting for testing, validation recommended</br> 
**Mentor:** </br>
**Difficulty:** Medium (need to learn about [Strict Mode](https://docs.microsoft.com/en-us/powershell/module/microsoft.powershell.core/set-strictmode?view=powershell-7.1))  </br>

### Microsoft Powershell #7: Add Timeout parameter to Invoke-Command cmdlet  
**Description:** 
Add a Timeout parameter to the Invoke-Command cmdlet so that we can invoke commands synchronously with timeouts. </br>
**Additional Info:** [https://github.com/PowerShell/PowerShell/issues/5434](https://github.com/PowerShell/PowerShell/issues/5434)
**Language:** C#</br>
**Skills/Background:** C#, PowerShell scripting for testing, validation recommended</br> 
**Mentor:** </br>
**Difficulty:** Medium </br>

### Microsoft Powershell #8: Add tab completion for Scope parameters
**Description:** 
A handful of PowerShell cmdlets take a Scope parameter, which dictates the scope of paths to consider for the context. The Scope parameter should have defined set of validated values which can be discovered through tab completion, so that it’s easy for a user to explore and not open to just any values. </br>
**Additional Info:** [https://github.com/PowerShell/PowerShell/issues/8106](https://github.com/PowerShell/PowerShell/issues/8106)
**Language:** C#</br>
**Skills/Background:** C# recommended</br> 
**Mentor:** </br>
**Difficulty:** Advanced (lot of example code, but finding right example) </br>

### Microsoft Powershell #9: Get-Member cmdlet should support inspecting a .NET type/instance’s implemented interfaces and members  
**Description:** 
If a concrete type or instance is provided to Get-Member, the cmdlet should be able to inspect and display the interfaces the instance, as well as members of the instance, implement. Additionally, given an interface type directly examine its members. Lastly, given a concrete instance or type list just its implemented interfaces’ types. To do so, students may have to create new values for -View parameter that Get-Member will support. </br>
**Additional Info:** [https://github.com/PowerShell/PowerShell/issues/13865](https://github.com/PowerShell/PowerShell/issues/13865)
**Language:** C#</br>
**Skills/Background:** C#, reflection in C#, Object Oriented Programming recommended</br> 
**Mentor:** </br>
**Difficulty:** Advanced </br>

### Microsoft Powershell #10: Add TimestampHashAlgorithm parameter to Set-AuthenticodeSignature cmdlet  
**Description:** 
The Set-AuthenticodeSignature cmdlet adds an authenticode signature to any file, including PowerShell script files, which is used to verify that the file hasn’t been tampered with since when it was signed. We wish to add a TimestampHashAlgorithm, which will take a hash algorithm and use that to create a hash with the timestamp. The hash created with the timestamp will track the creation/modification time of the file and ensure that it wasn’t able to be modified with past the time used in the signature hash. </br>
**Additional Info:** [https://github.com/PowerShell/PowerShell/issues/5092](https://github.com/PowerShell/PowerShell/issues/5092)
**Language:** C#</br>
**Skills/Background:** C#, Security recommended</br> 
**Mentor:** </br>
**Difficulty:** Medium (especially if already familiar with security) </br>

## Lutece Projects


Template: 
### project #: Title
**Description:** 
stuff </br>
**Expected outcomes:** 
**Language:** </br>
**Skills/Background:** </br> 
**Mentor:** </br>
**Difficulty:** Easy/Medium/Hard </br>
