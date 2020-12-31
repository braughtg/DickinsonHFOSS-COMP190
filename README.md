represents# Dickinson H/FOSS - Tools and Techniques for Software Development (COMP 190)

## Introduction:

Beginning in Fall 2016 Dickinson College began offering a year-long senior capstone course in which students engage with Free and Open Source Software (FOSS) projects and often those with  humanitarian objectives (i.e. HFOSS projects).  A [full report on this capstone](https://github.com/braughtg/DickinsonHFOSS-SFC-Materials) and its materials is also available. Based on our experiences with this senior capstone we significantly redesigned our curriculum beginning fall 2019 so that the knowledge, experiences and technical skill development necessary for H/FOSS participation occurs earlier and is distributed across a sequence of courses.

The first course in that sequence is COMP 190 - Tools and Techniques for Software Development, which has the following course description:

> An introduction to the Unix command line environment, shell scripting, system administration, debugging tools and version control. Skills developed will be applied in the context of a Humanitarian Free and Open Source Software (HFOSS) project. Case studies of social, legal and ethical issues raised by computing and computing for the greater good will complement the technical skill development.

Our website contains the full details of the [Dickinson computer science curriculum](https://www.dickinson.edu/homepage/402/computer_science_curriculum) and highlights the H/FOSS course sequence (190/290/390/491/492).

This repository will be a static snapshot and review of the materials for the COMP 190 course following its first offering in fall 2020. Please feel free to reach out if you are interested in the most recent materials.

## Course Context:

COMP 190 - Tools and Techniques for Software Development has been designed to be taken in the first semester of a student's second year. It is a required course for both computer science majors and minors, but is also open to any student.  Prior to taking COMP 190, students will have completed two introductory computer science courses, typically with one being procedural (Python) and one being object oriented (Java). However, these prerequisites primarily serve to ensure maturity in the discipline rather than the specifics of any particular programming language or paradigm.

Dickinson counts courses rather than credit hours and COMP 190 counts as 1/2 course (equivalent to 2 credit hours). As such, the course would, under non-Pandemic conditions, meet for 75 minutes once per week for 14 weeks plus a three-hour final exam period each semester. To reach 1/2 course credit, there would be a nominal expectation of 3 to 4 hours of work outside of class each week.

The semester in which this course was developed and first offered  (fall 2020) was taught remotely due to the COVID-19 pandemic. This presented numerous challenges. The result was that there were 11 instead of 14 meetings, meetings were shortened to 10-20 minutes to adapt to asynchronous video delivery, and hands-on activities were designed to be completed with asynchronous support. Upon reflection, these meetings and activities should be readily and effectively adaptable to in-person instruction. Full 75-minute meetings would provide time for discussion, question and answer, opportunities to review past activities, exploration of enrichment topics and for students to begin work on the current activities.  The course is set to be offered in-person in fall 2021.

## Course Outline & Materials:

The course can be broken into three topics, each with individual course meetings and activities as outlined below. A brief description of each topic and the focus of each of its class meetings are provided.  For each class meeting the Power Point deck used for the introduction and the hands-on activities used are also provided.  All of the material can be downloaded as [a single zip file](materials/COMP190Materials.zip) as well.

#### A. Unix Introduction

Students use a virtual machine environment ([VirtualBox](https://www.virtualbox.org/)) to install a Linux operating system ([LinuxLite](https://www.linuxliteos.com/)). They then use this environment to develop facility with the command line interface, common gnu/linux tools and filters, simple shell scripting for task automation and performing basic system administration tasks such as installing software and managing users, groups and permissions.

1. __Operating Systems & Virtual Machines:__ [Slide Deck](materials/01-S-OSandVM.ppt) | [Activity Sheet](materials/01-A-OSandVM.docx)
1. __Shell Commands:__ [Slide Deck](materials/02-S-UnixAndShell.ppt) | [Activity Sheet](materials/02-A-UnixAndShell.docx)
1. __Command Line Tools and Filters:__ [Slide Deck](materials/03-S-UnixTools.ppt) | [Activity Sheet](materials/03-A-UnixTools.docx)
1. __Shell Scripting:__ [Slide Deck](materials/04-S-ShellScpriting.ppt) | [Activity Sheet](materials/04-A-ShellScpriting.docx)
1. __Basic System Administration:__ [Slide Deck](materials/05-S-SystemAdmin.ppt) | [Activity Sheet](materials/05-S-SystemAdmin.docx)

#### B. Free and Open Source Software

Students begin to explore FOSS ideas and techniques.  They look at the range of intellectual property rights (copyright, trademark, design, patent) and learn about Open Source licenses. They gain experience with the use of version control via git and GitHub (easily adapted to GitLab) and issue trackers in the context of FOSS projects. The traditional automake tools are used to build a FOSS project and provide practice resolving dependency issues. Finally, Docker is introduced as a mechanism for simplifying the setup of FOSS development environments.

6. __Intellectual Property, Sofware Licencing and FOSS:__ [Slide Deck](materials/06-S-LicensingFOSS.ppt) | [Activity Sheet](materials/06-A-LicensingFOSS.docx)
1. __Version Control & a Branching Workflow:__ [Slide Deck](materials/07-S-VersionControl.ppt) | [Activity Sheet](materials/07-A-VersionControl.docx)
   - The materials for this class require that the instructor fork the Calculator project in the [github_issues_activity-f18 repository](https://github.com/braughtg/github-issues-activity-f18) then clone the issues to the forked repository using a tool such as [github-issues-import](https://github.com/IQAndreas/github-issues-import).
1. __Version Control & Merge Conflicts:__ [Slide Deck](materials/08-S-MergeConflicts.ppt) | [Activity Sheet](materials/08-A-MergeConflicts.docx)
1. __Building a FOSS Project: _The gnu Autotools & Dependencies_:__ [Slide Deck](materials/09-S-BuildingAProject.ppt) | [Activity Sheet](materials/09-A-BuildingAProject.docx)
1. __Docker for FOSS Development:__ [Slide Deck](materials/10-S-Docker.ppt) | [Activity Sheet](materials/10-A-Docker.docx)

#### C. Humanitarian Free and Open Source Software Participation

Students explore the structure, licensing and documentation of a number of mature HFOSS projects. This provides a basis for assessing and suggesting improvements to our own [FarmData2 project](https://github.com/DickinsonCollege/FarmData2) project.  Students ultimately have several opportunities to contribute to FarmData2 through the confirmation/refinement/clarification of issues and by making pull requests that improve documentation.

11. __H/FOSS Communities and FarmData2:__ [Slide Deck](materials/11-S-FarmData2.ppt) | [Activity Sheet](materials/11-A-FarmData2.docx)
    - The latter parts of these activities are based on the state of the [FarmData2 project](https://github.com/DickinsonCollege/FarmData2) at the time of writing.  Those activities will need to be updated and adapted as the FarmData2 project progresses.  Alternatively, it would be relatively straight forward to adapt these activities to another H/FOSS project as well.

## Student Surveys & Analysis

Students were asked to complete a Likert-scale pre/post course survey to assess their attitudes towards H/FOSS and their perceptions of the knowledge that they gained in the course.  The questions asked in the survey were identical for the pre/post surveys. The questions on the survey and the breakdown of student agreement with each before and after the course are shown in Figure 1.  The [full survey](materials/COMP190PrePostSurvey.pdf) is also available as a pdf.

[![Survey Results](materials/SurveyResults.png)](materials/SurveyResults.png)

__Figure 1__: Pre/post course survey question and results.  Each bar repreents 100% of student responses with the size of each color representing the fraction of students that expressed the indicated level of agreement. The pre-survey was completed by n=20 students and the post-survey was completed by n=14 students. Click the image for a higher resolution version.



6 women - all completed
14 men pre, 8 men post


## Reflections & Improvements

Pandemic related limitations...

- Enhance 6.

- Kitainerize and automate 7 and 8.

- 9 and 10 move to another mature HFOSS project
  - extend by 1 and add debugging here?

- 11 Expand to include more contribution to FarmData2
  - Break 11 into three + final project
  - communities in mature HFOSS
  - FarmData2 specifically - documentation and issue focused
  - contributions?



---
## Acknowledgements:

Partial support for the development of these materials has been provided by:
* A grant from [foss2serve](http://foss2serve.org/index.php/Main_Page) through the [Software Freedom Conservancy](https://sfconservancy.org/) (July 2020-September 2020).

* NSF Grant

* GNOME CEC

* Tim, Matt
* Mike S and Farm OS
* Allen NPFI
* Michael Skalak
* Heidi, Stony, Karl

* All of the students in COMP 190 at Dickinson College in fall 2020.

I want to thank the following for providing invaluable resources that gave me  pointers to readings and/or inspired and informed the activities for this course:

* Ryan's Tutorials

* Karl Fogel for his book [Producing Open Source Software: How to Run a Successful Free Software Project](https://producingoss.com/en/index.html)
* Greg DeKoenigsberg, Chris Tyler, Karsten Wade, Max Spevack, Mel Chua and Jeff Sheltren for their book [Practical Open Source Software Exploration: How to be Productively Lost, the Open Source Way](https://quaid.fedorapeople.org/TOS/Practical_Open_Source_Software_Exploration/html/index.html)
* Everyone who has contributed to the  [Learning Activities page on foss2serve](http://foss2serve.org/index.php/Category:Learning_Activity). Many of the materials for this course were adopted, adapted or inspired by the excellent activities on that page.

---
#### Licensing:

![Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png "Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License")
###### All textual materials provided in this repository are licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc/4.0/)
