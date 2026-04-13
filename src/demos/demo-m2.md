# Local Event Finder

## Purpose

The app is designed to search for, view, and plan local events. Users can:
- find and join events;
- create their own events;
- receive notifications;
- filter events by category, time, and number of participants.
Target audience: active users interested in local events (e.g., concerts, workshops, meetups).

## Problem

Many people find it difficult to quickly find interesting local events and plan to attend them. Existing platforms often do not allow users to filter events by time, category, or accessibility, which reduces their user-friendliness.
The app allows users to search for, view, and plan their participation in local events using an interactive map and convenient filters. It also lets users create their own events, receive notifications, and manage attendee lists, taking into account age restrictions and maximum capacity.

## Target Audience

Active users interested in attending local events, such as concerts, workshops, gatherings, and other social events.

## User Stories + MoSCoW

### MUST HAVE
- **User Authentication & Security**
    - [**User Registration:** As a new user I want to register in the system To access the app's features](./../user-stories.md#user-registration)
    - [**Log In:** As a new user I want to register in the system To access the app's features](./../user-stories.md#log-in)
    - [**Restricted access for guests:** As a guest I want to be restricted from accessing events and map So that only registered users can use core features](./../user-stories.md#restricted-access-for-guests)
- **Core Map Experience**
    - [**Viewing Events on a Map:** As a user I want to see events on an interactive map So I can easily navigate and choose events that interest me](./../user-stories.md#viewing-events-on-a-map)
- **Essential Actions**
    - [**Creating an Event:** As a user I want to create my own event So that other users can join it](./../user-stories.md#creating-an-event)
    - [**Quickly Join an Event:** As a user I want to quickly join an event with a single click So I don’t have to waste time on complicated steps and can confirm my attendance right away](./../user-stories.md#quickly-join-an-event)
- **Validation & Rules**
    - [**Age and Participant Limit Restrictions:** As a user I want to see and take into account participant limit restrictions, but not see events with age restrictions So that I can only join events that are available to me](./../user-stories.md#age-and-participant-limit-restrictions)
- **Technical Foundation**
    - [**Basic Responsive Interface:** As a user I want to be able to use the app comfortably on different devices (PC, phone) So I can access its features anytime and from any device](./../user-stories.md#basic-responsive-interface)

### SHOULD HAVE
- **Discovery & Organization**
    - [**Event Filtering:** As a user I want to filter events by category, tag, city, and time To quickly find interesting events that match my preferences](./../user-stories.md)
    - [**Personal Event List:** As a user I want to see a list of events I’m subscribed to or have created So I can easily manage my participation and keep track of upcoming events](./../user-stories.md#personal-event-list)
- **Communication**
    - [**Event Notifications:** As a user I want to receive notifications about upcoming events I’m subscribed to So I don’t miss out on interesting events](./../user-stories.md#event-notifications)
- **Advanced UX**
    - [Password Recovery ("Forgot Password" flow). Criteria from **Log In**](./../user-stories.md#log-in)

### COULD HAVE
- **Advanced UX**
    - [**Preventing Participation in Overlapping Events:** As a user I want to be unable to join events with overlapping times To avoid scheduling conflicts](./../user-stories.md#preventing-participation-in-overlapping-events)
    - [Map Pin Clustering (grouping nearby icons). Criteria of **Viewing Events on a Map**](./../user-stories.md#viewing-events-on-a-map)

### WON'T HAVE
- **Social & Analytics**
    - Public Participant List (seeing other users' profiles).
    - In-app comment sections for events.
    - Detailed Analytics Dashboard for event organizers.

## Roadmap MVP

### MVP 
- [Preoretizeded user stories](#user-stories--moscow).

### v1.1 (post-course)
- [Develop all user stories](#user-stories--moscow)
- Public Participant List (seeing other users' profiles).
- Advanced filters (tags, AM/PM, popularity).
- Notification settings in profile.
- Improved UX/UI (animations, ease of navigation).
- Event search by keywords.
- Event sorting (by date, popularity).

### v1.2 (further development)
- Full-featured real-time notifications.
- Recommendation system (personalized events).
- Advanced user profile.
- User traffic and activity analytics.
- Mobile version.
- Offline mode.
- In-app comment sections for events.
- Detailed Analytics Dashboard for event organizers.

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
