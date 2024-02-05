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
