# User Stories

## User Registration

As a new user   
I want to register in the system   
To access the app's features

Registration Requirements
- Form with email and password
- Email validation
- Password must be:
  - Must be at least 8 characters long.
  - Must contain at least one lowercase letter (a–z).
  - Must contain at least one uppercase letter (A–Z).
  - Must contain at least one digit
- Registration confirmation

## Log In

As a registered user   
I want to log in   
To access my profile and events

Acceptance Criteria
- Login form with email and password
- Password recovery option
- Error message for incorrect credentials

## Viewing Events on a Map

As a user   
I want to see events on an interactive map   
So I can easily navigate and choose events that interest me

Acceptance Criteria
- A map with event pins
- Color-coded events (current / upcoming)
- Clicking on a pin opens a preview of the event

## Creating an Event

As a user   
I want to create my own event   
So that other users can join it

Acceptance Criteria
- A form with a title, description, time, and location
- The ability to set a maximum number of participants and age restrictions
- The ability to edit or delete the event
- The ability to set event as canceled

## Event Notifications

As a user   
I want to receive notifications about upcoming events I’m subscribed to   
So I don’t miss out on interesting events

Acceptance Criteria
- Notifications about upcoming events (email or push)
- Ability to enable/disable notifications in the profile

## Event Filtering

As a user   
I want to filter events by category, tag, city, and time   
To quickly find interesting events that match my preferences

Acceptance Criteria
- Ability to select one or more event categories
- Filtering by tags (e.g., “concert,” “workshop”)
- Filtering by location (city, country)
- Filtering by time (date and time of day AM/PM)
- Applying multiple filters simultaneously
- Displaying only available events (participant limit not exceeded, age-appropriate)

## Personal Event List

As a user   
I want to see a list of events I’m subscribed to or have created   
So I can easily manage my participation and keep track of upcoming events

Acceptance Criteria
- Display all events the user is subscribed to
- Display all events created by the user
- Color-code current and upcoming events
- Ability to quickly “Join” / “Unjoin” directly from the list
- Sort by date, category, tag
- Hide events if the user does not meet the age requirement or the event is full


## Quickly Join an Event

As a user   
I want to quickly join an event with a single click   
So I don’t have to waste time on complicated steps and can confirm my attendance right away

Acceptance Criteria
- The “Join” button is available on the event card and on the event page
- Joining happens with a single click without any extra steps
- After clicking, the button changes to “Unjoin”
- The user receives confirmation (visual or via notification)
- The event is automatically added to the user’s personal list
- You cannot join if the event is full or does not match your age

## View full event details

As a user
I want to see detailed information about the event
So I can determine if it’s right for me and decide whether to attend

Acceptance criteria
- The event title is displayed
- A detailed description is displayed
- The date and time are listed
- The venue (location) is listed
- The event organizer is displayed
- The number of participants and maximum capacity are visible
- Age restrictions are specified (if any)
- The “Join” / “Unjoin” button is available
- List of participants (optional or partial)

## Age and Participant Limit Restrictions

As a user
I want to see and take into account participant limit restrictions, but not see events with age restrictions
So that I can only join events that are available to me

Acceptance criteria
- The event’s age restriction is displayed, but the event is not shown to users who do not meet the age requirement
- The current number of participants and maximum capacity are displayed
- You cannot join an event if the participant limit has been reached
- You cannot join an event if the user does not meet the age restriction
- Unavailable events are marked or hidden in the list
- The user receives a notification/message when attempting to join an unavailable event

## Basic Responsive Interface

As a user
I want to be able to use the app comfortably on different devices (PC, tablet, phone)
So I can access its features anytime and from any device

Acceptance Criteria
- The interface displays correctly on desktops, tablets, and mobile devices
- Responsive design (responsive design)
- Easy navigation between main pages (map, events, profile)
- Legible text and correct display of UI elements
- Fast page loading
- Basic accessibility (buttons, forms, and interactive elements work correctly)

## Preventing Participation in Overlapping Events

As a user
I want to be unable to join events with overlapping times
To avoid scheduling conflicts

Acceptance Criteria
- The event time is checked when attempting to join
- If the event overlaps with one already added, joining is prohibited
- The user sees an error message (e.g., “This event overlaps with another event in your schedule”)
- The message specifies the reason for the rejection (time conflict)
- The system correctly handles partial time overlaps
