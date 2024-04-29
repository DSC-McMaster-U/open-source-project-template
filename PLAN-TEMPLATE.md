# GDSC Open Source Project Requirements & Document Template

## Table of Contents  
[Purpose](#purpose)  
[Project Description](#-project-description)  

[Sprint Planning](#sprint-planning)  

## Purpose 
### What is this?
This template is meant to serve as a guideline for open source project leads planning, and documenting their projects, as well as managing their team of developers. You, as a lead, can begin filling out this project once you have a rough idea of what the project will be. Every project is different, so I'd like to emphasize that its a guideline, and can be adapted and expanded upon to meet your project's needs. Every project should, however, abide by the scrum agile team development framework, and following this guideline will facilitate that. If you have any questions/comments about this document, please don't hesitate to contact me, @rawamily on discord. 

### Who's this for?
This document is for both the lead and developers reference. Once this document is complete, it will be provided to the general open source applicants (i.e. your prospective developers), as they'll be choosing which project they want to commit to, so make sure to make it appealing! That being said you, asw the lead, are free to continue making edits to this document throughout the projects timeline, and you likely will need to, however **please have it completed prior to the start of the project in September**. Planning early will make your job as a lead a lot easier during the semester as you balance this role with other commitments, so start as soon as you can!


### How should I fill it out?
It's recommended to follow the markdown template provided. You can copy the contents of this file and commit it to your project's repository, so that applicants will have easy access to it. Note that the actual guidelines start in the following section, [Project Desctiption](#project-description), so you shouldn't have this section, [Purpose](#purpose), in the final document. Each section/sub-section contains instructions for you as the lead to fill it out. All the instructions are italicized, and again, they shouldn't be in the final document so please comment them out.  

## :bulb: Project Description
*Brief overview of the project, its objectives, and its significance. The list of objectives should briefly define **what** the project accomplishes. The list of stakeholders should briefly define **who** the main users/people affected by this project are. This section should provide context for the team, and should also provide them with any technical background information needed to understand the problem being addressed by your project. Feel free to include links/references to projects or whatever else that inspired you.*

### Objectives
1. Objective 1
2. Objective 2
3. Objective 3

### Stakeholders

- Stakeholder 1
- Stakeholder 2
- Stakeholder 3


## :compass: Implementation Plan

### Project Timeline
*Describe the major project milestones that you will aim for over the course of the year. Milestones should be oriented around the level of completeness your project attains toward the end product. It's a good idea to have Milestone 1 be a minimum viable product, something that satisfies the main business logic of the product with minimal code, then work to improving the project through following milestones. That was you can insure a working product by the end of the year.*

- **Milestone 1 (MVP):** Description, Date
- **Milestone 2:** Description, Date
- **Milestone 3:** Description, Date
- ...

### Tech Stack
*Determine a list of options for your tech stack. Ideally at this point, you'd list multiple frameworks that you'd pick from later, after onboarding your developers, so that you know what your team mates are most comfortable/interested in working with.*
- **Frontend Framework:** [e.g., React, Angular, Vue.js]
- **Backend Framework:** [e.g., Node.js, Django, Spring Boot]
- **Database:** [e.g., PostgreSQL, MySQL, MongoDB]
- **Other Technologies/Libraries:**
  - Technology 1
  - Technology 2
  - ...

### Project Structure 
*Describe the high-level structure of the project, including directories, modules, and how components/modules interact. For instance, you may need a frontend directory and a backend directory. In your backend directory you may have a designated module for different components of the project, etc. Keep it high level and don't include biolerplate. Include a diagram if you'd like!*

### API Documentation
*Optional: Include some high-level descriptions of the APIs that will need to be developed. You can organize this however you'd like.*
- **API Endpoint:** [URL]
- **API Documentation Tool:** [e.g., Swagger, Postman]
  
### Testing & CI/CD
*Your project should have a formal testing plan that will complement the code acceptance of each pull request. It be great if you could integrate automated testing and deployment, but manual testing works as well. Describe the test plans, metrics/measures you may use such as coverage, and tools you may use such as specific testing frameworks that match your tech stack, automation tools like GitHub Actions, Jenkins, etc.*

### Hosting 
*Optional: if you plan to use services to host and deploy the application list them below. Later on, you can append an architecture diagram to this section.*
- **Application Hosting:** [e.g., GKE, AWS, Heroku, Azure]
- **Database Hosting:** [e.g., AWS RDS, MongoDB Atlas]
- **Additional Services:** [e.g., CDN, Email Service Provider]


<!-- ### Deployment
- **Deployment Process:** [e.g., Manual, Automated]
- **Deployment Environment:** [e.g., Staging, Production]
- **Rollback Plan:** Describe the plan in case of deployment failures. -->

<!-- ### Documentation

- **Code Documentation:** [e.g., JSDoc, JavaDoc]
- **User Guide:** Provide a link or location for the user guide.
- **API Reference:** Link to the API documentation. -->


## :clipboard: Team Management

### Team Members
*For now, determine approximately how many developers and of what type you would need for your project. After recruitment and onboarding, list the names that will fulfill each role*
- **Scrum Master:** [Lead's Name]
<!-- - **Product Owner:** [Name] -->
- **Frontend Developers:**
  - [Name]
  - [Name]
  - [Name]
- **Backend Developers:**
  - [Name]
  - [Name]
  - [Name]


### Team Communication
- **Communication Platform:** Discord
- **Meeting Schedule:**
  - Daily Standup: [Time and Frequency]
  - Sprint Review: [Time and Frequency]
  - Sprint Retrospective: [Time and Frequency]
  - Other Meetings: [Specify]

### Roles and Responsibilities
- **Scrum Master:**
  - Facilitate scrum ceremonies
  - Remove impediments
  - Coach team on Agile practices
- **Product Owner:**
  - Define product backlog
  - Prioritize user stories
  - Accept/reject deliverables
- **Developers:**
  - Develop features
  - Collaborate with Product Owner
  - Participate in testing
- **Testers:**
  - Create test cases
  - Execute tests
  - Report defects

- **Collaboration Tools:** [e.g., Jira, 


## Sprint Planning



### Sprint Duration
- **Sprint Length:** [e.g., 2 weeks]
- **Start Date:** [Date]
- **End Date:** [Date]

### High Level Sprint Goals
1. Goal 1
2. Goal 2
3. Goal 3

### User Stories (Sample)

| ID   | User Story                                  | Priority | Story Points | Assignee |
|------|---------------------------------------------|----------|--------------|----------|
| US01 | As a [user role], I want to [feature]       | High     | 5            | Dev A    |
| US02 | As a [user role], I want to [feature]       | Medium   | 3            | Dev B    |
| US03 | As a [user role], I want to [feature]       | Low      | 2            | Dev C    |

### Sprint Tasks
- **Task 1:** Description, Assignee, Estimated Time
- **Task 2:** Description, Assignee, Estimated Time
- **Task 3:** Description, Assignee, Estimated Time


### Definition of Done
- Code Complete
- Passed Code Review
- Passed Unit Tests
- Integrated with Main Branch
- Documentation Updated

