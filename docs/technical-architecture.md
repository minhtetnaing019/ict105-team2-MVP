# Technical Architecture

## Project Title
**Peer Tutoring Booking Platform**

## 1. Selected Prototype Platform
**Frontend + localStorage or JSON**

## 2. Architecture Decision
The team has a mix of frontend skills (HTML/CSS/JavaScript) and backend/database skills (Python/SQL), but the prototype scope — four Must-Have features demonstrating tutor search, availability display, booking requests, and profile listing — does not require a hosted database or server. A frontend-only build backed by a local JSON data file (or `localStorage`) lets the team demonstrate the full booking flow end-to-end, keeps hosting free and simple (e.g. GitHub Pages), and avoids backend infrastructure risk within a single semester. If time allows, the team may extend storage to Firebase/Supabase to persist bookings across sessions/devices, but the MVP does not depend on this.

## 3. Main Components

| Component | Description | Tool / Technology | Related Requirement |
|---|---|---|---|
| User Interface | Shared layout/navigation used across all screens | HTML/CSS, consistent nav component | FR-13 |
| Data Input Form | Booking request form with client-side validation | HTML forms + JavaScript | FR-03, FR-10 |
| Data Storage | Stores tutor and booking records | JSON file or `localStorage` | FR-04 |
| Record List | Tutor search/listing screen, filterable by subject | JavaScript (filter/search logic) | FR-06 |
| Detail View | Tutor profile detail screen | HTML/CSS + JavaScript | FR-07 |
| Admin Function | Admin view to update booking status and manage tutor listings | JavaScript (status update logic) | FR-09 |
| Dashboard / Summary | Student "My Bookings" view and booking status display | HTML/CSS + JavaScript | FR-05, FR-08, FR-12 |

## 4. What Will Be Fully Implemented?
- Homepage (FR-01)
- Tutor search/listing by subject (FR-06)
- Tutor detail view with availability (FR-07)
- Booking request form with validation and confirmation message (FR-02, FR-03, FR-10, FR-11)
- Booking storage to JSON/localStorage (FR-04)
- Student booking list / status view (FR-05, FR-08)
- Admin view to update booking status (FR-09)
- Consistent navigation across all screens (FR-13)

## 5. What Will Be Simulated?
- Real tutor accounts/authentication — tutors will be represented as static seed data rather than a full sign-up system.
- Admin dashboard statistics (FR-12) will use the sample booking dataset rather than live aggregated data from many real users.
- Mobile responsiveness (FR-14) will be simulated with responsive CSS rather than tested on a full device matrix.
- Data privacy controls (FR-15) will be simulated by simply omitting sensitive fields from the UI, rather than implementing real access-control/authentication.

## 6. Final Prototype Risk
The biggest technical risk is that a frontend-only, `localStorage`-based data layer does not persist or sync data across different users' browsers/devices, which could make a live multi-user demo (e.g. student books, admin approves) look disconnected. The team will reduce this risk by using a single shared JSON dataset for the demo walkthrough and, if time permits, migrating booking storage to a lightweight shared backend (Firebase/Supabase) so status updates make by the admin are visible to the student view in real time.
