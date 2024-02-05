# Project Requirements Document

## Executive Summary

This SCALE project is meant to be a platform designed for empowering community-based organizations. The product will be a combination of a project management tool and an impact reporting tool. The essential functionality of this product will be its impact reporting functionality where project members may enter data into forms that will be aggregated with municipal, provincial, and federal data to provide qualitative and quantitative information about the project’s societal and environmental impact. Individuals using this product include organizations, project managers, and project team members. This product will be used to report the impact organizational projects have in the community as well as to help project managers organize their project and team members.

## Project Glossary

**Social Impact:** Refers to the impact the project has on at a societal level as well as on the 17 Sustainable Development Goals established by the United Nations

## User Stories
### Account-related features and login features
#### US 1.01 - Organization Sign-Up 
As an organization, I want to be able to create an organization account, so that I can manage my project and team through the application.
**Acceptance Tests**
1. User cannot sign up with an invalid email
2. User cannot sign up with an email of an existing account
3. User cannot sign up if they are missing an entry field
4. User can sign up with all fields filled out and a valid email

#### US 1.02 - Organization Authentication
As an organization, I want to be able to sign into my organization account, so that I can access the application’s functionalities for managing my project and team.
**Acceptance Tests**
1. User can sign in with a correct email and correct password
2. User cannot sign in with a correct email and incorrect password
3. User cannot sign in with an incorrect email and correct password
4. User cannot access the app’s functionalities without signing in

#### US 1.03 - Team Role Assigning
As an organization, I want users to have different assigned roles, so that team members can be easily identified and managed.
**Acceptance Tests**
1. User’s role matches what was assigned to them or was selected by them
2. User’s role is saved for future logins

#### US 1.04 - Team Role Permissions
As an organization, I want users to have different permissions based on their roles, so that the organization can maintain structure and control in project and team management.
**Acceptance Tests**
1. User can access features available to their role
2. User cannot access features not available to their role
3. User can access data available to their role
4. User cannot access data not available to their role

#### US 1.05 - User Sign-Up
As a user, I want to be able to create an account, so that I can work on projects and provide social impact data related to the projects.
**Acceptance Tests**
1. User cannot sign up with an invalid email
2. User cannot sign up with an email of an existing account
3. User cannot sign up if they are missing an entry field
4. User sign up with all fields filled out and a valid email

#### US 1.06 - User Authentication
As a user, I want to be able to sign into my account, so that I can access the application’s functionalities for working on the project and tasks I am assigned to.
**Acceptance Tests**
1. User can sign in with a correct email and correct password
2. User cannot sign in with a correct email and incorrect password
3. User cannot sign in with an incorrect email and correct password
4. User cannot access the app’s functionalities without signing in

### Project-related features
#### US 2.01 - Create Projects
As an organization, I want to be able to add projects to the application, so that I can use the application’s features for my projects.
**Acceptance Tests**
1. The project is added and shows on the dashboard
2. A duplicate project cannot be added
3. The project cannot be added if required fields are not filled out

#### US 2.02 - Describe Projects
As an organization, I want my added projects to display descriptions and objectives, so that people viewing the projects can understand the projects and/or our organization.
**Acceptance Tests**
1. Descriptions and objectives can be added to project
2. Descriptions and objectives are saved
3. Descriptions and objectives are visible in-app

#### US 2.03 - Sustainable Development Goal (SDG) Selection
As an organization, I want to be able to specify the intended sustainable development goal (SDG) of my projects, so that we can set a defined goal to reach to measure our projects’ relative success.
**Acceptance Tests**
1. SDG can be selected
2. SDG can be set for project
3. SDG can be saved

#### US 2.04 - Edit Project Information
As an organization, I want my added projects’ information to be editable, so that changes in project plans can be easily accommodated in the application.
**Acceptance Tests**
1. User can edit project information
2. Edited project information is saved

#### US 2.05 - Task Progress Quantification
As an organization, I want tracked tasks to be viewed in the context of social impact metrics, so that our projects’ progress towards meeting goals can be measured.
**Acceptance Tests**
1. Task progress is quantified
2. Task data is correctly retrieved

#### US 2.06 - Project Status Quantification
As an organization, I want project statuses to be viewed in the context of social impact metrics, so that our projects’ statuses can be measured.
**Acceptance Tests**
1. Project status is quantified
2. Project status data is correctly retrieved

#### US 2.07 - Create Gantt Charts
As an organization, I want to be able to create Gantt charts for project planning, so that I can visualize project schedules, dependencies, and milestones.
**Acceptance Tests**
1. User can create Gantt charts
2. Users who do not belong to the team cannot create Gantt charts
3. Gantt charts are saved
4. Gantt charts are visible to relevant parties
5. Gantt charts contain accurate information

#### US 2.08 - Create Encryption & Secure Access Protocols
As an organization I want there to be encryption and secure access protocols, so that confidential data is not being leaked or altered.
**Acceptance Tests**
1. Data is encrypted
2. Data is only accessed securely

### User-related features
#### US 3.01 - Add Users to Project
As a project manager, I want to add users to my project as a team member, so they can use the features provided by the application.
**Acceptance Tests**
1. Existing users can be added to an existing project
2. Added team members are saved
3. Users who does not belong to the project cannot be assigned a task
4. Non-existent users cannot be added to an existing project
5. Users cannot be added to a non-existing project

#### US 3.02 - Create Tasks
As a project manager, I want to be able to create tasks and specify details about them, so that I can split up my project into smaller detailed parts.
**Acceptance Tests**
1. User can assign priorities to tasks
2. User can set due dates for tasks
3. Task details are saved

#### US 3.03 - Assign Tasks
As a project manager, I want to be able to assign tasks to team members, so that the relevant parties know what tasks there are to be completed.
**Acceptance Tests**
1. Team members can be assigned tasks
2. Assigned tasks are visible to all relevant parties
3. Tasks remain assigned to the user until completed or removed

#### US 3.04 - Allocate Resources
As a project manager, I want resource allocation to take team member availability into account, so that project tasks can be accomplished without obstructions.
**Acceptance Tests**
1. Tasks can be assigned to an available team member
2. Tasks cannot be assigned to an occupied team member
3. Tasks can be assigned to a user after that user has completed a previous task

#### US 3.05 - Add Tasks to Schedules
As a project manager, I want to add tasks to schedules, so that I can keep track of what tasks should be being worked on.
**Acceptance Tests**
1. User can drag and drop tasks into the schedule
2. Tasks are correctly inputted into the schedule
3. User can edit the schedule
4. Changes to schedules are saved

#### US 3.06 - Track Task Progress
As a user, I want to be able to track progress in project tasks, so that we can track overall progress for the project.
**Acceptance Tests**
1. Tasks can be assigned different levels of progress
2. Users can assign progress level to tasks assigned to them
3. Users cannot assign progress level to tasks of other users
4. Tasks progress levels are accurate

#### US 3.07 - Track Project Progress
As a user, I want to be able to view the progress of plans and tasks that I am a part of, so that I can track overall progress for the project.
**Acceptance Tests**
1. User can view the progress of plans they are assigned to
2. User can view the progress of tasks they are assigned to
3. Plan progress is accurate
4. Task progress is accurate

#### US 3.08 - Search For Tasks
As a user, I want to be able to search and filter for tasks, so that I can more easily find the task I am looking for.
**Acceptance Tests**
1. Task that appear in the results match the selected filters
2. Tasks that match the filter successfully appear in the list

#### US 3.09 - Remove Tasks
As a user, I want to be able to remove tasks, so that I can visually see that I no longer need to work on the task.
**Acceptance Tests**
1. Task does not exist
2. Task does not show in the list

### File related features
#### US 4.01 - Upload Files
As a user, I want to be able to upload project-related files to a centralized file repository, so that they can be conveniently stored and accessed.
**Acceptance Tests**
1. Files can be uploaded to storage

#### US 4.02 - Download Files
As a user, I want to be able to download project-related files, so that I can access and edit them as needed.
**Acceptance Tests**
1. Files can be downloaded from storage

#### US 4.03 - Organize Files
As a user, I want to be able to organize project-related files, so that they are more organized and can be more easily accessed.
**Acceptance Tests**
1. Folders can be created
2. Files can be moved into folders
3. Files can be taken out of folders

#### US 4.04 - Categorize Documents
As an organization, I want to be able to categorize documents by project and type, so that they are organized and easier to access.
**Acceptance Tests**
1. The correct project is assigned to the document
2. The correct document type is assigned to the document

#### US 4.05 - Add Comments
As a user, I want to be able to leave comments on documents, so that other team members can take note of them when reviewing a document.
**Acceptance Tests**
1. Comments are displayed
2. Comments show up on the correct document

#### US 4.06 - View Document Version Changes
As a user, I want to be able to see version changes on documents, so that I am aware of how recent a document I am reviewing is.
**Acceptance Tests**
1. Version changes are recorded
2. Version history is accurate

### Metric and data related features
#### US 5.01 - Input Metric Data
As a user, I want to be able to input data related to social impact metrics, to be used for reporting.
**Acceptance Tests**
1. Frequency of data collection can be added
2. Data sources can be added
3. Predefined social impact metrics can be used
4. Metrics update after data is inputted

#### US 5.02 - Track Metric Progress
As a user, I want to be able to track the progress of metrics, so that I can see the projects’ progress.
**Acceptance Tests**
1. Metrics can be tracked by project
2. Metrics can be tracked over time

#### US 5.03 - Associate Data With Project
As a user, I want to be able to associate data with specific projects and provide context for them, so that I can later see the social impact of the specific project.
**Acceptance Tests**
1. Project-related data can be retrieved
2. Project-related data can be quantified

#### US 5.04 - Use Analytic Tools
As a user, I want to be able to use analytic tools, so that I can analyze data about project progress.
**Acceptance Tests**
1. Built-in data analytics tools can be accessed
2. Trend analysis can be created

#### US 5.05 - Define Social Impact Goals
As a user, I want to be able to define social impact goals for specific metrics, so that our team can work towards those goals.
**Acceptance Tests**
1. Target values for goals can be set
2. Deadlines for goals can be set
3. Goals are saved

#### US 5.06 - Compare Social Impact Performance
As a user, I want to be able to compare social impact performance with industry standards, so that I can ensure I am following the required standards.
**Acceptance Tests**
1. Industry standards for specific metrics can be selected
2. Industry standard is correctly applied

### Impact report data features
#### US 6.01 - Assign Permissions For Data Reporting
As a project manager, I want to assign user roles and permissions to team members in data reporting, so that only certain individuals can report about specific data.
**Acceptance Tests**
1. User can report data available to their role
2. User cannot report data not available to their role

#### US 6.02 - Visualize Data
As a user, I want to be able to visualize data in various formats, so that I can gain deeper insights about the project’s social impact.
**Acceptance Tests**
1. Visualized data can be interacted with
2. Visualization options can be selected for each metric

#### US 6.03 - View Geolocation Data
As a user, I want to be able to view data on maps, so that I can track the social impact of the project using location.
**Acceptance Tests**
1. Map can be opened from the application
2. Intended data is displayed on the map
3. Displayed data is accurate, in terms of both location and content

#### US 6.04 - Track Project Performance
As a user, I want to be able to track project performance, so that I can gain insight on project progress.
**Acceptance Tests**
1. Benchmark data can be viewed
2. Benchmarks for specific metrics can be selected
3. Performance changes can be viewed over time

#### US 6.05 - View Project Data With Impact Data
As a user, I want to be able to access project management data within the social impact reporting tool, so that I can see the project progress in relation to its social impact.
**Acceptance Tests**
1. Project management data is displayed within the social impact reporting tool
2. Project data retrieved is correct

### Report features
#### US 7.01 - Create Social Impact Report
As an organization, I want to be able to create reports that represent the associated projects’ progress in meeting specified goals and social impact metrics, so that they can be accessed and viewed by others.
**Acceptance Tests**
1. Fields in the templates can be filled in
2. Quantitative data is presented
3. Narrative descriptions can be created alongside quantitative data
4. Success stories and testimonials can be inputted
5. Reporting methodologies can be inputted

#### US 7.02 - Input Compliance Information
As a user, I want to include compliance information in my social impact reports, so that I can track and mitigate sources of risk in the organization.
**Acceptance Tests**
1. User can input compliance information into the report
2. SDG compliance standards are included in the report

#### US 7.03 - Have Predefined Report Templates
As an organization, I want to be able to have report templates with defined fields for creating reports, so that reports can be easy to both read and write.
**Acceptance Tests**
1. Report templates can be retrieved from the application
2. Report templates can be used by the user

#### US 7.04 - Export Report
As an organization, I want to be able to export reports in various formats, so that they can be accessed and read by others.
**Acceptance Tests**
1. Reports can be exported
2. Reports can be exported in different formats

#### US 7.05 - Share Project Impact Report
As an organization, I want reports to be accessible to the relevant parties, so that they can view the social impact of our projects.
**Acceptance Tests**
1. Reports are accessible to those who are relevant to the information in the report
2. Reports are not accessible to those who are relevant to the information in the report

#### US 7.06 - Configure Report
As an organization, I want to ensure reports can be configured, so that they align with certain regulations.
**Acceptance Tests**
1. User can configure reports
2. Report configurations are saved
3. Users without permission cannot configure reports

#### US 7.07 - Access Predefined Project Status Report
As a user, I want to be able to access pre-defined project status reports, so that I can get insight into project performance.
**Acceptance Tests**
1. User can view project status reports of projects they are involved in
2. User cannot view project status reports of projects they are not involved in
3. Project status report data is accurate
4. Project status report data is from taken from the correct project

#### US 7.08 - Customize Report Parameters
As a user, I want to be able to customize report parameters, so that the reports display accurate data.
**Acceptance Tests**
1. Date ranges can be customized
2. Data fields can be customized

### Mobile features
#### US 8.01 - Mobile Compatibility
As a user, I want to be able to use the application on a mobile device, so that I can access the app at any time in a convenient manner.
**Acceptance Tests**
1. Application view can adapt to a smaller view resolution
2. User can use the application’s features can be used through a mobile device

### MoSCoW
#### Must Have
* US 1.01 - Organization Sign-Up 
* US 1.02 - Organization Authentication
* US 1.05 - User Sign-Up
* US 1.06 - User Authentication
* US 2.01 - Create Projects
* US 2.02 - Describe Projects
* US 2.03 - Sustainable Development Goal (SDG) Selection
* US 2.07 - Create Gantt Charts
* US 2.08 - Create Encryption & Secure Access Protocols
* US 3.01 - Add Users to Project
* US 3.02 - Create Tasks
* US 3.03 - Assign Tasks
* US 3.05 - Add Tasks to Schedules
* US 3.06 - Track Task Progress
* US 3.09 - Remove Tasks
* US 5.01 - Input Metric Data
* US 5.02 - Track Metric Progress
* US 5.04 - Use Analytic Tools
* US 5.05 - Define Social Impact Goals
* US 6.02 - Visualize Data
* US 7.01 - Create Social Impact Report
* US 7.02 - Input Compliance Information
* US 7.03 - Have Predefined Report Templates
* US 7.04 - Export Report
* US 7.08 - Customize Report Parameters

#### Should Have
* US 1.03 - Team Role Assigning
* US 2.04 - Edit Project Information
* US 2.05 - Task Progress Quantification
* US 2.06 - Project Status Quantification
* US 3.04 - Allocate Resources
* US 3.07 - Track Project Progress
* US 3.08 - Search For Tasks
* US 4.01 - Upload Files
* US 4.02 - Download Files
* US 4.03 - Organize Files
* US 4.04 - Categorize Documents
* US 4.05 - Add Comments
* US 4.06 - View Document Version Changes
* US 5.03 - Associate Data With Project
* US 5.06 - Compare Social Impact Performance
* US 6.03 - View Geolocation Data
* US 7.05 - Share Project Impact Report

#### Could Have
* US 1.04 - Team Role Permissions
* US 6.01 - Assign Permissions For Data Reporting
* US 6.04 - Track Project Performance
* US 6.05 - View Project Data With Impact Data
* US 7.06 - Configure Report
* US 7.07 - Access Predefined Project Status Report

#### Would Like But Won’t Get
* US 8.01 - Mobile Compatibility

## Similar Products

* [monday.com](https://monday.com)

## Open Source Products/Inspiration

* [shadcn/ui](https://ui.shadcn.com/) and [shadcn/ui GitHub](https://github.com/shadcn-ui/ui)
  * Used for inspiration for the UI design and layout of the website.

* [Tremor](https://www.tremor.so/)
  * Used for inspiration with charts/data visualization.

## Technical Resources
### Backend: Next.js Server Actions + (Relational Database)
* [Next.js Documentation](https://nextjs.org/docs)

### Deployment: Cybera + ???
* [Cybera Documentation](https://wiki.cybera.ca/display/RAC/)

### Frontend: Next.js TypeScript + Tailwind CSS
* [Next.js Documentation](https://nextjs.org/docs)
* [Tailwind CSS Documentation](https://v2.tailwindcss.com/docs)

# Code Commit Message Conventions
Use the following format for commit messages and making branches:

- `feat`: A new feature
- `fix`: A bug fix
- `docs`: Changes to documentation
- `style`: Formatting, missing semi colons, etc; no code change
- `refactor`: Refactoring production code
- `test`: Adding tests, refactoring test; no production code change
- `chore`: Updating build tasks, package manager configs, etc; no production code change
- `perf`: A code change that improves performance
- `ci`: Changes to CI configuration files and scripts; no production code change

# Software Design

## High-Level Architecture Diagram

## ER Diagram

## Sequence Diagrams

## Low-Fidelity User Interface

# Project Management

This page provides a general overview of the assigned tasks and roles for the duration of five sprints (subject to change).

## Story Map

## Project Plan
### Sprint 1
*Due: February 5*
| Task      | Related US | Assigned To | Due Date |
| ----------- | ----------- | ----------- | ----------- |
| User Stories    | Documentation       | Hieu Truong/Jan Chow       | Feburary 5       |
| Acceptance Tests    | Documentation       | Hieu Truong/Jan Chow       | Feburary 5       |
| MoSCoW    | Documentation       | Jan Chow       | Feburary 5       |
| Similar Products Documentation    | Documentation       | Akarshan Mishra       | Feburary 5       |
| Open-source Projects/Inspiration Documentation      | Documentation       | Akarshan Mishra       | Feburary 5       |
| Technical Resources Documentation    | Documentation       | Jan Chow       | Feburary 5       |
| Architecture Diagram    | Documentation       | Title       | Feburary 5       |
| ER Class Diagram    | Documentation       | Title       | Feburary 5       |
| Low-Fidelity User Interface    | Documentation       | Akarshan Mishra       | Feburary 5       |
| Story Map    | Documentation       | Jordan Atkins       | Feburary 5       |
| Project Plan    | Documentation       | Hieu Truong       | Feburary 5       |
| Team Canvas    | Documentation       | Jordan Atkins       | Feburary 5       |
| Belbin Roles    | Documentation       | Jordan Atkins       | Feburary 5       |

## Sprint 2
*Due: February 26*
**User Stories**
| User Story    | Story Points |
| ----------- | ----------- |
| US 1.01 - Organization Sign-Up      | 2       |
| US 1.02 - Organization Authentication   | 2        |
| US 1.05 - User Sign-Up   | 2        |
| US 1.06 - User Authentication   | 2        |
| US 2.01 - Create Projects   | 3        |
| US 2.02 - Describe Projects   | 2        |
| US 2.03 - Sustainable Development Goal (SDG) Selection   | 1        |
| US 2.07 - Create Gantt Charts   | 5        |
| US 3.01 - Add Users to Project   | 2        |
| US 3.02 - Create Tasks   | 3        |
| US 3.03 - Assign Tasks   | 3        |
| US 3.05 - Add Tasks to Schedules   | 3        |
| US 3.06 - Track Task Progress   | 2        |
| US 3.09 - Remove Tasks   | 1        |
| US 5.01 - Input Metric Data   | 2        |
| US 5.02 - Track Metric Progress   | 5        |
| US 5.04 - Use Analytic Tools   | 5        |
| US 5.05 - Define Social Impact Goals   | 2        |
| US 7.03 - Have Predefined Report Templates   | 5        |

Estimated Sprint Velocity: **52**

**Tasks**
