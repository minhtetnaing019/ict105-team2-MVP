# Initial IT Venture Idea Log
 
## Idea 1: Campus Ride-Share Coordination App
### Problem Area
Students who commute from the same areas have no easy way to coordinate carpooling, leading to unnecessary travel costs and traffic congestion around campus.
### Target Users
University students who commute by private car or rideshare from off-campus locations.
### Current Alternative
Students post in LINE or Facebook group chats informally, which is disorganized and hard to search.
### Proposed IT Solution
A web or mobile app where students can post and browse ride offers by route, time, and available seats, and contact each other to coordinate.
### Possible Technology
HTML/CSS/JS frontend, Google Maps API for route display, Google Sheets or Firebase as a lightweight backend, basic user login.
### Why This Is Suitable
The core features — posting, browsing, and filtering — can be prototyped quickly with standard web tools. No payment integration is needed for an MVP, keeping the scope manageable within a semester.
 
---
 
## Idea 2: Student Assignment Deadline Tracker
### Problem Area
Students juggle deadlines from multiple courses across different platforms (LMS, LINE, email), making it easy to miss submissions.
### Target Users
University students managing coursework across several subjects simultaneously.
### Current Alternative
Students rely on personal notebooks, phone reminders, or memory, often leading to missed or last-minute submissions.
### Proposed IT Solution
A web-based dashboard where students can manually log deadlines by subject, view a unified calendar, and receive browser-based reminders.
### Possible Technology
HTML/CSS/JS, localStorage or Firebase for data persistence, a calendar library such as FullCalendar.js, browser notification API.
### Why This Is Suitable
The system requires no complex integrations. A fully functional prototype with CRUD operations and a calendar view can realistically be built and tested within a single semester.
 
---
 
## Idea 3: Canteen Menu & Queue Status Board
### Problem Area
Students waste time walking to the canteen only to find long queues or that their preferred stall is closed, especially during short lunch breaks.
### Target Users
University students and staff who eat at the campus canteen during peak hours.
### Current Alternative
Students physically check the canteen or ask peers — there is no centralized, real-time information available.
### Proposed IT Solution
A simple web board where canteen vendors can update their menu and open/closed status each day, visible to any student via a shared link or campus screen.
### Possible Technology
HTML/CSS/JS, Firebase Realtime Database for live updates, a simple vendor-side form for data entry, no login required for students.
### Why This Is Suitable
The system has two clearly scoped interfaces — a vendor update form and a student-facing display board — both achievable with basic web development and a free-tier database within a semester.
 
---
 
## Idea 4: Peer Tutoring Booking Platform
### Problem Area
Students who need academic help struggle to find qualified peers willing to tutor, while students who want to tutor have no visible channel to offer their help.
### Target Users
Undergraduate students seeking tutoring and those willing to provide it across various subjects.
### Current Alternative
Students ask around in class or post in group chats, which reaches a limited audience and has no scheduling structure.
### Proposed IT Solution
A web platform where tutors can list their available subjects and time slots, and students can browse and book sessions with them.
### Possible Technology
HTML/CSS/JS, Google Sheets or Firebase as a backend, a simple booking form, email or LINE notification on confirmation.
### Why This Is Suitable
The booking flow is straightforward and can be prototyped without a payment system. The platform demonstrates database design, form handling, and basic scheduling logic — all achievable within a semester project.
 
---
 
## Idea 5: Classroom Seat Availability Checker
### Problem Area
Students arriving early to free-period classrooms often find them fully occupied or reserved, with no way to know in advance which rooms have open seats.
### Target Users
University students looking for available study spaces or classrooms outside of scheduled class time.
### Current Alternative
Students wander between rooms to check manually, wasting time especially in large campus buildings.
### Proposed IT Solution
A web app that displays real-time or schedule-based seat availability per room, allowing students to check before heading over and optionally mark a seat as taken.
### Possible Technology
HTML/CSS/JS, Firebase Realtime Database, room schedule data entered manually or imported from a spreadsheet, optional QR code check-in per room.
### Why This Is Suitable
The prototype can start with manually entered schedule data and a simple availability display, avoiding complex integrations. Core features can be developed and demonstrated within a semester.
 
---
 
## Idea 6: Campus Event Aggregator
### Problem Area
University clubs and departments announce events across multiple platforms — LINE groups, Facebook pages, bulletin boards — making it hard for students to discover what is happening on campus.
### Target Users
University students interested in attending campus events, and student organizations looking to promote their activities.
### Current Alternative
Students follow multiple separate channels and still miss events; organizers cannot reach the full student body easily.
### Proposed IT Solution
A centralized web page where clubs and departments can submit upcoming events, and students can browse all events in one place filtered by category or date.
### Possible Technology
HTML/CSS/JS, Google Forms for event submission, Google Sheets as a data source, a JS frontend that reads and displays the sheet data, basic category filter.
### Why This Is Suitable
Using Google Forms and Sheets as the backend removes the need to build an admin panel from scratch, allowing the team to focus on the student-facing interface and filtering logic — a realistic scope for a semester prototype.

