# Event-Flow : Event Management Platform

## Overview
EventFlow is an event management platform for handling registrations and interactions between organizers and attendees. This repository contains a prototype with functionalities for attendee registration, event management, and engagement scoring.

## Technologies Used
Frontend: React.js

Backend: Node.js

Database: MySQL

## Features
Attendee Dashboard: Secure registration/login, view and manage event registrations.

Organizer Dashboard: Mocked login, create/edit/delete events, view attendee registrations.

Backend APIs: CRUD operations, data encryption.

Engagement Scoring: Calculate scores based on registrations, attendance, responsiveness, and feedback.

Audit Logging: Maintain logs of actions taken by attendees and organizers.

Access the app at http://localhost:3000.

## Approach
### Clone the Repository

```
git clone https://github.com/aasthadewangan11/Event-Flow.git
cd Event-Flow
```

### Install Dependencies

```
npm install
```

### Run the Application

```
npm start      # for frontend React apps
npm run dev    # for development server
```


## Security
Basic authentication with JWT.

Passwords encrypted using bcrypt.
