# Work Readiness Digital Portfolio

*Student Name:* Thimna Barbara Booi 

*Student Number:* 230232108 

*Subject Code:* PRP372S  

*Lecturer:* P. Inderlal  

*Date:* 30 March 2026  

---

## Overview
This portfolio demonstrates my progress and learning outcomes during the Work Readiness Training program.  
Each section contains evidence of learning and a reflection based on the *STAR (Situation, Task, Action, Result)* technique.

---

# CV Submission

## Thimna Barbara Booi
---
Address: Gugulethu, Cape Town | Contact: 0726924142 | Email: 230232108@mycput.ac.za | LinkedIn: www.linkedin.com/in/thimnabooi 

### Career Objectives
Motivated ICT student with hands-on experience in software development, database management, UI/UX design, and data analysis. Seeking an entry-level opportunity to apply my technical skills, contribute to innovative projects, and grow within the IT industry.

### Education
**Table View High School - 2017-2019**
* Matric - Admission to a bachelor's degree

**Cape Peninsula University of Technology - 2023-Present**
* DPICT: Applications Development

### Experience
**IT Learnership | Siyaya Skills Institution | 2021 - 2022**
* Undertook comprehensive training in Microsoft Excel, covering beginner to intermediate/advanced functions, and completed competency-based logbooks documenting practical tasks and applied learning.

### Projects
**UI/UX Design Project - FIGMA - 2025**
* Watched YouTube videos and completed LinkedIn courses to learn more about FIGMA. Created wireframes and high-fidelity mockups using FIGMA.

**Ambumate - JAVA-based Medical Support System - 2024**
* Contributed to the development of a Java Swing healthcare application. Designed and implemented the profile and medical history sections.

### Technical Skills
Java | Python | JavaScript | MySQL | HTML | CSS | FIGMA | Microsoft Excel

### References
**Geraldine Hartman**
* Job title: Lecturer
* Company: Cape Peninsula University of Technology
* Contact: 0745243546

**Candice Pape**
* Mentor
* Contact: 0780515075

## Reflection on coding in Markdown: STAR method
**Situation -** I was required to code my CV using Markdown Language

**Task -** I was tasked with coding my CV using Markdown

**Action -** I carefully coded my CV using Markdown and ensured that it was correct

**Result -** I submitted the link to my CV on MS Teams

---

# Mock Interview

<video width="600" controls>
  <source src="video/mock video.mp4" type="video/mp4">
</video>

## Reflection on mock interview video experience: STAR method
**Situation -** I was required to record a mock interview video

**Task -** I had to answer interview questions while recording myself

**Action -** I took multiple videos to ensure that it was correct

**Result -** I submitted the video to my digital portfolio

---

# Published on GitHub Pages

## Reflection on the use of GitHub Pages: STAR method
**Situation -** I was required to deploy my portfolio to GitHub Pages

**Task -** I had to figure out how to use GitHub Pages and deploy my work

**Action -** I deployed my portfolio to GitHub Pages

**Result -** I was able to publish my portfolio successfully

---

# Agile Team Charter

## Evidence
**Project Overview**

The BeeHive to Purple Bee Integration Project aimed to investigate how meeting action items recorded in BeeHive could be transferred into Purple Bee as tasks. The purpose is to reduce manual data entry, improve task management, and ensure that action items identified during meetings could be followed up more efficiently.

The proposed integration allows authorised X Spark employees to transfer approved action items from BeeHive into the Purple Bee task-management system, where they could be managed under the relevant Thematics.

**Team Roles and Responsibilities**

The project involved dividing responsibilities between team members, while also working as a team to ensure that the research covered the different components of the proposed integration.

* Project Lead and Documentation Lead – Thimna Booi: I was responsible for coordinating the project, researching BeeHive and Purple Bee, contributing to the integration requirements, and compiling the final documentation, while leading the presentation
* Purple Bee Research: Responsible for investigating Purple Bee's functionality and identifying how it could receive and manage transferred tasks.
* Database Research: Responsible for researching the database requirements and how information would be stored and managed across the systems.

**Project Objectives**

* Understand how BeeHive manages meeting agendas, notes, and action items.
* Investigate how Purple Bee manages tasks.
* Identify how information could be transferred between the two systems.
* Establish the functional and technical requirements for the proposed integration.
* Consider security, authentication, data validation, and duplicate prevention.
* Produce final documentation to guide future implementation.

![BeeHive to Purple Bee Project Overview](evidence/project%20overview.png)

![Development Team](evidence/Development%20Team.png)

## Reflection - STAR Method
**Situation -** The team was assigned a project to investigate the integration of BeeHive and Purple Bee. The objective was to reduce the need for employees to manually recreate meeting action items as tasks in another system.

**Task -** As the Project Lead and Documentation Lead, I was responsible for coordinating the work, researching the BeeHive and Purple Bee systems, and ensuring that the findings and requirements were properly documented.

**Action -** I investigated how BeeHive handles meeting information and action items, contributed to identifying the integration requirements, and worked with the team to bring the different research areas together. I also helped ensure that the final documentation clearly explained the proposed solution and its requirements.

**Result -** The team produced final research and requirements documentation that outlined how the integration could work and presented it. This experience helped me understand the importance of teamwork, task allocation, communication, and proper documentation when working on a software development project.

# User Stories and Tasks

## Evidence
**User Story**
As an authorised X Spark team member, I want approved action items from BeeHive meetings to be transferred into Purple Bee as tasks, so that the team can manage and follow up on meeting responsibilities without manually entering the same information again.

**Tasks Identified**
1. Investigate how BeeHive stores and manages meeting action items.
2. Identify the information required to create a task in Purple Bee.
3. Define the data structure and fields that need to be transferred.
4. Identify the API or Supabase Edge Function required to receive task information.
5. Establish authentication and authorisation requirements.
6. Identify validation rules to ensure that incoming task information is complete and correct.
7. Investigate how duplicate task creation can be prevented.
8. Document the expected responses and error-handling requirements.
9. Identify how the integration could be tested in a staging environment.

![Activity Diagram](evidence/activity%20diagram.png)

![Technical Requirements](evidence/technical%20requirements.png)

![User Story](evidence/user%20story.png)

## Reflection - STAR Method
**Situation -** During the integration research, it was important to understand what employees would need from the proposed system and how the integration would support their daily activities.

**Task -** My responsibility was to contribute to identifying and documenting the requirements that would guide the development of the integration.

**Action -** I helped define the purpose of the integration through a user story and considered the steps required to achieve it. This included identifying the information that needed to move between the systems and considering requirements such as authentication, validation, and preventing duplicate tasks.

**Result -** The user story and task breakdown provided a clearer understanding of what the proposed integration needed to accomplish. I learnt how user stories help translate business needs into practical software requirements and how individual tasks make a larger development goal easier to manage.

# Product Backlog

## Evidence
**Product Backlog Overview**
The product backlog contained the main features and requirements identified during the research. These items represented the work that would need to be completed during the future implementation of the integration.

| Priority | Backlog Item | Description |
| --- | --- | ---|
| High | Data structure | Define the information that must be transferred from BeeHive to Purple Bee. |
| High | Receiving endpoint | Establish an API or Supabase Edge Function to receive task information. |
| High | Authentication | Ensure that only authorised requests can create tasks. |
| High | Data validation | Validate incoming information before creating a task. |
| High | Duplicate prevention | Prevent the same action item from creating multiple tasks. |
| Medium | Response handling | Define successful responses and error messages. |
| Medium | Task creation records | Record the outcome of task-creation requests. |
| Medium | Staging tests | Test the proposed integration in a controlled staging environment. |

![Data Requirements](evidence/Data%20Requirements.png)

## Reflection - STAR Method
**Situation -** The project required the team to identify the different features and technical requirements that would be necessary to make the integration work.

**Task -** I needed to understand the requirements and contribute to organising the research findings into a structured document that could guide future development.

**Action -** I helped identify the important requirements, including the data structure, receiving endpoint, authentication, validation, and duplicate prevention. I also considered which requirements would be essential before the integration could function correctly and documented the proposed priorities.

**Result -** The product backlog provided a structured overview of the work required for future implementation. I gained a better understanding of how software requirements are prioritised and how a product backlog helps development teams plan and organise their work.

# Sprint Backlog

## Evidence
**Sprint Work and Activities**
The project work focused on research, requirements analysis, documentation, and technical preparation.

| Activity | Description | Outcome |
| --- | --- | --- |
| BeeHive research | Investigated how BeeHive manages meeting agendas, notes, and action items. | Better understanding of the source system. |
| Purple Bee research | Investigated how Purple Bee manages tasks and where transferred action items would belong. | Better understanding of the receiving system. |
| Integration research | Explored how the two systems could communicate through an API-based approach. | Identified the proposed integration approach. |
| Requirements analysis | Identified functional and technical requirements, including security and data validation. | Requirements documented for future implementation. |
| Final documentation | Consolidated the research, requirements, and proposed integration process. | Final project documentation completed. |
| OpenCode installation | Installed OpenCode as part of the technical setup and familiarisation with development tools. | OpenCode installation completed. |

![Purple Bee](evidence/PurpleBee.png)

![BeeHive](evidence/BeeHive.png)

![OpenCode Installation](evidence/opencode.png)

## Reflection - STAR Method
**Situation -** As the project progressed, the team needed to move from understanding the two systems to documenting a practical approach for integrating them. This required research, planning, and preparation.

**Task -** My responsibility was to complete my assigned research, contribute to the integration requirements, assist with the final documentation, and complete the relevant technical setup, as well as present our findings to the senior development team.

**Action -** I researched BeeHive and its functionality, investigated how meeting action items could be transferred, and documented the requirements for the proposed integration. I also helped consolidate the research into the final documentation. In addition, I installed OpenCode as part of becoming familiar with the technical tools available for the project.

**Result -** I completed my research and documentation responsibilities and successfully installed OpenCode. I developed a better understanding of how research and planning contribute to software development and learnt that technical preparation is an important part of getting ready for implementation.

# Agile Logbook

## Evidence
**Project Activity Log**

| Activity | Work performed | Outcome |
| --- | --- | --- |
| Project introduction | Reviewed the project objective and understood the purpose of connecting BeeHive and Purple Bee. | Established an understanding of the project. |
| BeeHive investigation | Researched BeeHive's meeting agendas, notes, and action-item functionality. | Identified the information that could be transferred. |
| Purple Bee investigation | Researched the task-management functionality and the Thematics area. | Identified where transferred tasks would be managed. |
| Integration investigation | Explored the proposed API-based communication between the systems. | Established the proposed direction for integration. |
| Requirements documentation | Identified functional and technical requirements, including authentication, validation, and duplicate prevention. | Created a structured requirements document. |
| Documentation finalisation | Consolidated the team's research and completed the final documentation. | Final documentation completed. |
| Technical preparation | Installed OpenCode as part of the project's technical setup. | Installation completed. |

**Requirements Document (Thursday, 10 September 2026)**

The pages below are from the BeeHive – Purple Bee final documentation, the main deliverable recorded in this logbook. The full PDF is available here: [BeeHive-Purple Bee Final Documentation](BeeHive-Purple%20Bee%20final%20documentation.pdf)

### Cover and table of contents (pages 2–4)

![Cover and table of contents – page 2](evidence/logbook/page-02.png)

![Cover and table of contents – page 3](evidence/logbook/page-03.png)

![Cover and table of contents – page 4](evidence/logbook/page-04.png)

### Project overview (pages 5–7)

![Project overview – page 5](evidence/logbook/page-05.png)

![Project overview – page 6](evidence/logbook/page-06.png)

![Project overview – page 7](evidence/logbook/page-07.png)

### Development team and devices (page 8)

![Development team and devices – page 8](evidence/logbook/page-08.png)

### Functional requirements and business rules (pages 9–10)

![Functional requirements and business rules – page 9](evidence/logbook/page-09.png)

![Functional requirements and business rules – page 10](evidence/logbook/page-10.png)

### Business use case model (page 11)

![Business use case model – page 11](evidence/logbook/page-11.png)

### User activities (page 12)

![User activities – page 12](evidence/logbook/page-12.png)

### Use case glossary and narratives (pages 13–15)

![Use case glossary and narratives – page 13](evidence/logbook/page-13.png)

![Use case glossary and narratives – page 14](evidence/logbook/page-14.png)

![Use case glossary and narratives – page 15](evidence/logbook/page-15.png)

### Activity diagram (pages 16–17)

![Activity diagram – page 16](evidence/logbook/page-16.png)

![Activity diagram – page 17](evidence/logbook/page-17.png)

### Interface requirements (page 18)

![Interface requirements – page 18](evidence/logbook/page-18.png)

### Performance requirements (page 19)

![Performance requirements – page 19](evidence/logbook/page-19.png)

### Security requirements (pages 20–21)

![Security requirements – page 20](evidence/logbook/page-20.png)

![Security requirements – page 21](evidence/logbook/page-21.png)

### Data requirements (pages 22–26)

![Data requirements – page 22](evidence/logbook/page-22.png)

![Data requirements – page 23](evidence/logbook/page-23.png)

![Data requirements – page 24](evidence/logbook/page-24.png)

![Data requirements – page 25](evidence/logbook/page-25.png)

![Data requirements – page 26](evidence/logbook/page-26.png)

### Integration and dependency requirements (pages 27–28)

![Integration and dependency requirements – page 27](evidence/logbook/page-27.png)

![Integration and dependency requirements – page 28](evidence/logbook/page-28.png)

### BeeHive and Purple Bee integration (pages 29–31)

![BeeHive and Purple Bee integration – page 29](evidence/logbook/page-29.png)

![BeeHive and Purple Bee integration – page 30](evidence/logbook/page-30.png)

![BeeHive and Purple Bee integration – page 31](evidence/logbook/page-31.png)

### Requirement IDs, priority and traceability (pages 32–33)

![Requirement IDs, priority and traceability – page 32](evidence/logbook/page-32.png)

![Requirement IDs, priority and traceability – page 33](evidence/logbook/page-33.png)

### Open questions, risks and constraints (pages 34–37)

![Open questions, risks and constraints – page 34](evidence/logbook/page-34.png)

![Open questions, risks and constraints – page 35](evidence/logbook/page-35.png)

![Open questions, risks and constraints – page 36](evidence/logbook/page-36.png)

![Open questions, risks and constraints – page 37](evidence/logbook/page-37.png)

## Overall Reflection - STAR Method
**Situation -** The BeeHive to Purple Bee Integration Project gave me the opportunity to work on a real-world software integration research task within the X Spark environment. The project required an understanding of two existing systems and how they could potentially communicate to improve an internal business process.

**Task -** My main responsibilities were to lead and document the research relating to BeeHive, contribute to identifying the integration requirements, and help ensure that the final documentation presented the proposed solution clearly and professionally.

**Action -** I investigated BeeHive's functionality, researched how meeting action items could be transferred into Purple Bee, and worked with the team to bring together the different research findings. I contributed to identifying the technical requirements, considered potential challenges, and helped compile the final documentation. I also installed OpenCode as part of my technical preparation.

**Result -** I completed my assigned research and documentation work, and the team produced a final document that could be used as a reference for future implementation. Although the actual integration was not implemented or tested during this research phase, I gained valuable knowledge about system integration, APIs, databases, software requirements, documentation, and project coordination.

Overall, this project helped me understand that software development involves much more than writing code. It also requires careful research, communication, planning, problem-solving, and the ability to document technical information in a way that other developers can understand and use.
