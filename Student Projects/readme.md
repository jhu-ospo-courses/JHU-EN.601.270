# Student Projects
Students will work on a student project through the semester to provide a real world example of the open source and engineering practices from class. 
Student projects have been developed by a set of mentors from a number real world open source licensed projects. 
Students will choose a project from the list below and apply for it by sending email to the instructor. 

## Open Source Student Projects 
1. [Semester.ly Student Projects](https://github.com/jhu-ospo-courses/JHU-EN.601.270/blob/main/Student%20Projects/readme.md#semesterly-projects): [Semester.ly](https://semester.ly/) is a web platform created by students for students to bring modern technology to the most difficult and archaic parts of higher education. You may well be using it yourself. Semester.ly projects cover a wide range of problems to be solved. 
2. [OpenCRAVAT Student Projects](https://github.com/jhu-ospo-courses/JHU-EN.601.270/blob/main/Student%20Projects/readme.md#opencravat-projects): [OpenCRAVAT](https://opencravat.org/index.html) is a new open source, scalable decision support system to support variant and gene prioritization. It is written in Python and developed in the [Karchin Lab](https://karchinlab.org/) at Johns Hopkins University in collaboration with In Silico Solutions with funding provided by the National Cancer Institute's ITCR program. 
3. PASS 
4. [Lutece](https://lutece-platform.github.io/): Lutece is a powerful Java™ based Content Management Framework developed by the [City of Paris](https://lutece.paris.fr/lutece/), and adopted in many places (including the St. Francis Neighborhood Center in Baltimore). 
5. Microsoft PowerShell 
6. Brigade


## Semester.ly Projects 
### Semester.ly #1: Revive Advanced Search Feature 
**Description:** 
Our current advanced search feature is broken and often inconvenient for the average user, we need want it to not only be fixed but be greater than its foundational concept. Advanced Search comprises of search by Dept., Area, Level, & Day/Time, but at the moment, there are bugs across all these filters. It needs to be either completely rewritten with a fresh set of eyes or the original system can be built upon and improved. The goal is to not only fix the advanced search feature but truly make it a seamless, more intuitive user experience.
**Language:** 
**Skills/Background:** Redux, React 
**Mentor:** Sebastian
**Difficulty:** Easy/Medium

### Semester.ly #2: New Social Features
#### Description: 
Textbook Marketplace, Links to Group chats, Links to new student projects, LinkedIn links, Improved User Profiles (choose profile pictures, adjust personal links, etc.), etc. are all ideas to increase social interactions between students.
At the moment, we have the Facebook integration to use the FB login and see friends in the same classes, but the social features are lacking. We can add many unique social features that don't conflict with typical social media platforms.
The goal is to create a stepping stone for regular social interactions with a variety of new social features (at a minimum 3-5 distinct ideas)
#### Language: 
#### Skills/Background: None
#### Mentor: Sebastian
#### Difficulty: Easy to Hard

### Semester.ly #3: Semester.ly API
#### Description: 
To enhance our partnership with UCredit as well as any other new student projects, we can create an API that simplifies accessing certain features unique to Semester.ly. An API (Application Programming Interface) communicates with an app and gets information in return. Semly can provide a gateway to simplifying course scheduling at a software level for developers interested in quickly integrating specific tools in Semester.ly into their projects or work cycle.
The goal is to create a working API that covers at least 50% of Semly's features.
#### Language: 
#### Skills/Background: Preferred: Django, Node, REST APIs Required: Basic understanding of REST APIs
#### Mentor: Sebastian or Ali
#### Difficulty: Easy to Hard

### Semester.ly #4: Course Recommendation System
#### Description: 
To ease students' worries about finding the "right" courses, Semly can have a Machine Learning (ML) model to create a course recommendation system. An ML model can be built from our Google Analytics, user surveys, course ratings, and other information to create course recommendations based on each major (or year, etc.). This requires being cautious with basic user information and focusing on developing something that can consistently improve over time with increased user interaction. The goal is to create a foundation for a fully functioning ML model. This must be well-documented and ideally, relatively simple for the future developers to contribute.
#### Language: 
#### Skills/Background: Required: Python, Thorough understanding of Machine Learning
#### Mentor: Sebastian or Ali
#### Difficulty: Hard

### Semester.ly #5: Course Evaluations API
#### Description:  
Discard previous Course Evaluations modal and create a new API connected with JHU Evaluations. At some point, we integrated Course Evaluations directly integrated with HTML files, but there must be a long-term solution to regularly update course evaluations and populate them across all courses. An API will be the simplest and best way to communicate with Hopkins public course evaluation statistics and allow students to suggest additional comments/reactions.
The goal is to create a new API to integrate course evaluations directly into Semester.ly. There can be a new basic dashboard to view course evaluations in a sleek and accessible format if time permits.
#### Language: 
#### Skills/Background: Preferred: Basic understanding of APIs, React, Redux, HTML/CSS 
#### Mentor: Ali or Sebastian
#### Difficulty: Medium to Hard

## OpenCRAVAT Projects
### OpenCRAVAT #1: Gene-centric annotation of noncoding elements 
### Description: 
Genes tend to be more well-annotated than noncoding regions. In many cases, a particular gene has evidence for relationship to noncoding elements that is made available by one or more data sources. In this project, we seek to enable users to identify variants within noncoding elements that are relevant to a particular gene (or set of genes). 
### Expected outcomes: Annotation module, filters 
### Skills/Background: Python programming, genetics background 
### Mentors: Kym Pagel, Rick Kim, or Kyle Moad 
### Difficulty: Medium    

### OpenCRAVAT #2: Gene set analysis 
### Description: 
The are around 20-30,000 genes in the human genome. Previous work has identified several subsets of these genes that are relevant to human conditions.  For example, several thousand genes are relevant to cancer. In this project, we aim to help users query and summarize variants within commonly used gene sets.  
### Expected outcomes: Annotation modules, filter interface modifications 
### Skills/Background:Python programming, genetics background 
### Mentors: Kym Pagel, Rick Kim, or Kyle Moad 
### Difficulty: Medium

### OpenCRAVAT #3: Variant Ranking
### Description: 
There are about 3 million variants in the average human genome, but a small set of these variants are relevant to human health. To make it easier to find these variants, we will create a variant ranking system that identifies variants that are likely benign, have uncertain impact, and are likely pathogenic. Gene-level features would play a strong impact here.
### Expected outcomes: Annotation module 
### Skills/Background: Python programming, biological knowledge
### Mentor: Kym Pagel
### Difficulty: Easy 

### OpenCRAVAT #4: Advanced visualization widgets for multiple mutations 
### Description: 
Assessing the distribution of variants in a given genome, gene or noncoding element is strongly benefited by visualization techniques. In this project, we will implement new graphical widgets to show users where variants occur within genes, regions, and genomes.  
### Expected outcomes: 2-3 visualization widgets 
### Skills/Background: Python programming, Javascript
### Mentors: Rick Kim or Kyle Moad
### Difficulty: Medium 

### OpenCRAVAT #5: Connection to Diverse Data Formats
### Description: 
Most users input VCF-formatted data, but these files can quickly become bulky for cohort-level data. Alternative data formats such as Genomic data structure (GDS) files are a more space and memory efficient alternative. In this project, we will build reporter and converter modules to help OpenCRAVAT handle this new data format, among other formats. 
### Expected outcomes: 2-3 converter modules 
### Skills/Background:Python programming 
### Mentors: Kym Pagel or Rick Kim 
### Difficulty: Medium

### OpenCRAVAT #6: Efficient Cloud computing 
### Description: 
Variant annotation through OpenCRAVAT is largely serial. On the cloud, Google BigQuery provides various annotation datasets such that each variant, or set of variants, can be queried simultaneously. In this project, we will edit the existing code of OpenCRAVAT to leverage the BigQuery data to more efficiently annotate variants in cloud environments.
### Expected outcomes: Dedicated cloud-computing module
### Skills/Background:Python programming, cloud computing expertise 
### Mentor: Kyle Moad 
### Difficulty: Medium 

## PASS Projects

## Lutece Projects

## Microsoft Powershell Projects

## Brigade

Template: 
### project #: Title
#### Description: 
#### Language: 
#### Skills/Background:  
#### Mentor:  
#### Difficulty: Easy/Medium
