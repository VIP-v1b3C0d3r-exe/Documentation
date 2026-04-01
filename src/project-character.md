# Project Character

Project character for `Local Event Finder` project.

## Comand information

| Role                  | Name                      | GitHub        | Email                                 |
| -                     | -                         | -             | -                                     |
| Team Lead + Backend   | Uladzislau Mikhayevich    | @exxecute     | uladzislau.mikhayevich@stud.esdc.lt   |
| Backend               | Ivan Samal                | @Skri1l       | ivan.samal@stud.esdc.lt               |
| Frontend              | Aliaxandra Nerush         | @alexanerush  | aliaksandra.nerush@stud.esdc.lt       |
| Frontend              | Sofya Asinskaya           | @ossofi       | sofya.asinskaya@stud.esdc.lt          |

## Project Description

### Problem

Many people find it difficult to quickly find interesting local events and plan to attend them. Existing platforms often do not allow users to filter events by time, category, or accessibility, which reduces their user-friendliness.

### Solution

The app allows users to search for, view, and plan their participation in local events using an interactive map and convenient filters. It also lets users create their own events, receive notifications, and manage attendee lists, taking into account age restrictions and maximum capacity.

### Target Audience

Active users interested in attending local events, such as concerts, workshops, gatherings, and other social events.


## Project Scope

The project scope is defined and maintained in the [User Story document](./user-stories.md), which outlines the functional requirements, expected behaviors, and key use cases of the system. It provides a structured description of features from the end-user perspective, including acceptance criteria and priorities.

This document serves as the primary reference for understanding what is included in the project scope, as well as for tracking changes, refinements, and the evolution of requirements throughout the development lifecycle.

## Technical stack

The project's technology stack is defined separately for each component and is described in detail in the corresponding repositories.

This document provides only a high-level overview of the project. The system architecture is described in an [additional document](./architecture.md), including how the components interact. Detailed information about the technologies, libraries, versions, and development tools used can be found in the documentation of each specific service.

## Risks

| Risk                                              | Probability | Impact | Mitigation                                                                                       |
| -                                                 | -           | -      | -                                                                                                |
| Lack of time to implement all features            | High        | High   | Prioritize MVP features; focus on core event search and creation first                           |
| Technical challenges with real-time notifications | Medium      | Medium | Start with basic email notifications; implement real-time updates later using WebSockets/SignalR |
| Team member illness or unavailability             | Low         | High   | Document tasks thoroughly; ensure knowledge sharing so any team member can take over             |
| Difficulty integrating interactive event map      | Medium      | High   | Use proven mapping libraries (e.g., Leaflet, Google Maps API) and allocate time for testing      |
| Low user adoption                                 | Medium      | High   | Conduct early user testing; gather feedback and adjust UX/UI to improve engagement               |
| Data privacy and compliance issues                | Low         | High   | Implement proper data handling, follow GDPR/CCPA guidelines, and encrypt sensitive user data     |
| Scope creep / adding too many features            | High        | Medium | Maintain clear project roadmap and review feature requests against MVP goals                     |

## Communication

- **Daily standup:** Monday - 11:30; Thursday - 11:00
- **Main Channel:** [MS Teams](https://teams.microsoft.com/l/channel/19%3AqBZ5c3wGeBAdoP-zXuujtZDLZg-kmUm2k15GiW_b8kc1%40thread.tacv2/Group%206?groupId=b642be3d-ef84-48ad-aa9a-c355e3703b1c&tenantId=b1bece90-2038-4afb-9f19-6bcd2a777a1c&ngc=true)
- **Code review:** GitHub Pull Requests
- **Task-tracker:** Jira

## Signs

| Contributor Name          | Sign  |
| -                         | -     |
| Uladzislau Mikhayevich    | Agree |
| Ivan Samal                | Agree |
| Aliaxandra Nerush         | Agree |
| Sofya Asinskaya           | Agree |
