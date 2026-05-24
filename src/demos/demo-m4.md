# Demo M4

## About

The app is designed to search for, view, and plan local events. Users can:
- create their own events;
- filter events by category, time, and number of participants.
- find and join events;

## Current test coverages

Current code coverage:   
![Code coverage](../../assets/demos/4/code-coverage/image.png)

## Planned User Stories

### User Registration

> As a new user I want to register in the system To access the app's features.

In current app version user can register his account:   
![User Registration](../../assets/demos/4/user-registration/image.png)

## Log In

> As a new user I want to register in the system To access the app's features

In current app version can log in his account:   
- ![Log In](../../assets/demos/4/log-in/log-in.png)
- ![Loggined In](../../assets/demos/4/log-in/loggined-in.png)

## Restricted access for guests

> As a developer I want to be restricted from accessing events and map So that only registered users can use core features

In current app version we have restriction access for guests:   
![Restricted access for guests](../../assets/demos/4/restricted-access-for-guests/image.png)

## Viewing Events on a Map

> As a user I want to see events on an interactive map So I can easily navigate and choose events that interest me

In current app version we have map with events:   
![Viewing Events on a Map](../../assets/demos/4/viewing-events-on-a-map/map.png)

Also maps shows current/upcoming events:   
- ![Upcoming event](../../assets/demos/4/viewing-events-on-a-map/upcoming.png)
- ![Current event](../../assets/demos/4/viewing-events-on-a-map/current.png)

## Creating an Event

> As a user I want to create my own event So that other users can join it.

In current app version we have event creation:
- By Clicking `+`:
  - ![Add Event](../../assets/demos/4/creating-an-event/add-event.png)
- Opens event creation menu:
  - ![Event Creation Menu](../../assets/demos/4/creating-an-event/event-creation-menu.png)

## Age and Participant Limit Restrictions

> As a user I want to other users take into account participant limit restrictions and not see events with age restrictions So that they can only join events that are available to them

- Creating Event With 21+:
  - ![Event Creation Menu](../../assets/demos/4/age-and-participant-limit-restrictions/event-creation.png)
  - ![Map Pin](../../assets/demos/4/age-and-participant-limit-restrictions/map-pin.png)
- The user that 18 yo sees:
  - ![No Map Pin](../../assets/demos/4/age-and-participant-limit-restrictions/no-pin.png)

TODO: Participants

## Basic Responsive Interface

> As a user I want to be able to use the app comfortably on different devices (PC, phone) So I can access its features anytime and from any device

It works from PC, phone:
- ![PC](../../assets/demos/4/viewing-events-on-a-map/map.png)
- ![Phone](../../assets/demos/4/basic-reponsive-interface/phone.jpg)

## Event Filtering

> As a user I want to filter events by category, tag, city, and time To quickly find interesting events that match my preferences

![Event Filtering](../../assets/demos/4/event-filtering/image.png)

## Not Completed User Stories

### Quickly Join an Event

In the current version of the app, it is not yet possible to connect to an event from the website, but this feature is currently under active development and is scheduled to be ready for future updates.

### Personal Event List

In the current version of the app, it is not yet possible to see joined events from the website, but this feature is currently under active development and is scheduled to be ready for future updates. However now In list user can see every created event as a test view for this presentation.

![Personal Event List](../../assets/demos/4/personal-event-list/image.png)

### Event Notifications

In the current version of the app, it is not yet possible to get events from the website, but this feature is currently under active development and is scheduled to be ready for future updates.

### Password Recovery

In the current version of the app, it is not yet possible recover password from the website, but this feature is currently under active development and is scheduled to be ready for future updates. In current time we have almost working algorithm and screen.

![Password recovery](../../assets/demos/4/password-recovery/image.png)

## Check Up

- [x] Backend API работает (аутентификация, CRUD)
- [x] Frontend подключён к API
- [x] База данных наполнена тестовыми данными
- [x] Основные user stories реализованы
- [x] Код покрыт unit-тестами (минимум 50%)

## Conclusion

Overall, the application is currently approximately 80% complete. Considering the current development progress, there is a high probability that the MVP will be successfully completed by the end of this course.
