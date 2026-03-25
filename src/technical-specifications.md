# Technical Specifications

## Revision

| Date          | Version   | Description           |
| -             | -         | -                     |
| 25.03.2026    | v0.0      | Initial Specification | 

## 1. Purpose

The app is designed to search for, view, and plan local events. Users can:
- find and join events;
- create their own events;
- receive notifications;
- filter events by category, time, and number of participants.
Target audience: active users interested in local events (e.g., concerts, workshops, meetups).

## 2. Platform

Web application: responsive desktop version.

## 3. Screens and Features

### 3.1 Home Page
Greeting, service description

### 3.2 Login/Sign Up
Email + password
Username, profile picture (optional)
Password recovery

### 3.5 Events map
Interactive map with event pins
All events codes by colors:
- Blue — upcoming events
- Green — current events
Clicking on a pin opens the event preview
Search button:
List of all available events with brief information
Filters: category, tags, date, city, country, time of day (AM/PM), popularity
Hide events if the user does not meet the age requirement or the event is full

### 3.4 Personal Event List
Events joined and created
Color coding: current and upcoming

### 3.5 Individual Event Page
Full details: title, description, location, time, organizer
List of participants, maximum capacity, age restriction
“Join” / “Unjoin” button

### 3.6 User Profile (low priority)
Basic information: username, avatar, email, age
List of your events
Notification settings (optional)

## 4. Key Features
- Event scheduling with color coding
- Subscription to upcoming events
- Filters by time of day (AM/PM)
- Restrictions on participants and age
- Hiding inappropriate events
- Notifications (low priority)

## 5. Note:
This document provides a high-level overview of the Local Event Finder application. Detailed technical specifications, including technology stack, API documentation, database schemas, and implementation guidelines, are maintained in the project’s respective frontend and backend repositories.
