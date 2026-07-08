# System Requirements

## Project
**Peer Tutoring Booking Platform**

## Purpose
This document defines the functional requirements (FR) for the MVP. Each requirement is derived directly from the Lab 04 user stories and acceptance criteria, and maps forward to the Lab 05 wireframes and prototype screens.

---

## Functional Requirements

### FR-01 — Homepage
**Description:** The system shall display a homepage that introduces the platform and provides a clear entry point for students to begin booking a tutor.
**Priority:** Must
**Related User Story:** US-01
**Acceptance Criteria:** Given a user opens the website, when the homepage loads, then the project title, description, and a "Book Tutor" button are visible.
**Wireframe Screen:** homepage.png

---

### FR-02 — Booking Process
**Description:** The system shall allow a student to complete an end-to-end process of selecting a tutor and booking a session.
**Priority:** Must
**Related User Story:** US-02
**Acceptance Criteria:** Given a student selects a tutor, when the booking process is completed, then a booking record is created successfully.
**Wireframe Screen:** input-form.png (part of the flow starting from record-list.png / detail-view.png)

---

### FR-03 — Booking Form Submission
**Description:** The system shall provide a form for students to submit tutoring session requests, including student name, subject, tutor selection, date, time, and notes.
**Priority:** Must
**Related User Story:** US-03
**Acceptance Criteria:** Given all required fields are completed, when the student clicks Submit, then the booking information is stored.
**Wireframe Screen:** input-form.png

---

### FR-04 — Booking Data Storage
**Description:** The system shall save all booking records to a data store so they can be retrieved and displayed later.
**Priority:** Must
**Related User Story:** US-04
**Acceptance Criteria:** Given a booking is submitted, when the data is saved, then the booking appears in storage (e.g. database, Firebase, or JSON file).
**Wireframe Screen:** N/A (backend/data layer — not a distinct screen)

---

### FR-05 — Booking List View
**Description:** The system shall display a list of the student's bookings so they can review their tutoring schedule.
**Priority:** Must
**Related User Story:** US-05
**Acceptance Criteria:** Given bookings exist, when the student opens "My Bookings," then all bookings are displayed.
**Wireframe Screen:** record-list.png / dashboard.png

---

### FR-06 — Tutor Search and Filter
**Description:** The system shall allow students to search and filter tutors by subject so they can quickly find a suitable tutor.
**Priority:** Must
**Related User Story:** US-06
**Acceptance Criteria:** Given tutor data exists, when a student searches by subject, then matching tutors are displayed.
**Wireframe Screen:** record-list.png

---

### FR-07 — Tutor Detail View
**Description:** The system shall display detailed tutor information, including subjects taught, biography, schedule, and contact information, so students can choose the best tutor.
**Priority:** Must
**Related User Story:** US-07
**Acceptance Criteria:** Given a student selects a tutor, when the tutor profile opens, then detailed information is displayed.
**Wireframe Screen:** detail-view.png

---

### FR-08 — Booking Status Tracking
**Description:** The system shall show the current status of a booking (e.g. Pending, Approved, Completed) so students know whether their request has been actioned.
**Priority:** Must
**Related User Story:** US-08
**Acceptance Criteria:** Given a student has a booking, when they view it, then the current booking status is shown.
**Wireframe Screen:** dashboard.png / admin-view.png

---

### FR-09 — Admin Booking and Tutor Management
**Description:** The system shall allow administrators to update booking status and manage tutor approvals so students receive accurate information.
**Priority:** Must
**Related User Story:** US-09
**Acceptance Criteria:** Given a booking or tutor application exists, when the admin updates its status, then the new status is saved and displayed.
**Wireframe Screen:** admin-view.png

---

### FR-10 — Form Validation
**Description:** The system shall validate required fields on the booking form so incomplete bookings cannot be submitted.
**Priority:** Must
**Related User Story:** US-10
**Acceptance Criteria:** Given required fields are empty, when the student submits the form, then validation messages appear.
**Wireframe Screen:** input-form.png

---

### FR-11 — Confirmation Messaging
**Description:** The system shall display a confirmation message after a successful booking so students know their request went through.
**Priority:** Must
**Related User Story:** US-11
**Acceptance Criteria:** Given a booking is successful, when submission finishes, then a success message is displayed.
**Wireframe Screen:** input-form.png

---

### FR-12 — Admin Dashboard Summary
**Description:** The system shall provide a dashboard showing booking statistics so administrators (and students, for their own activity) can monitor tutoring activity at a glance.
**Priority:** Must
**Related User Story:** US-12
**Acceptance Criteria:** Given booking data exists, when the dashboard opens, then summary information is displayed.
**Wireframe Screen:** dashboard.png

---

### FR-13 — Consistent Navigation
**Description:** The system shall maintain a consistent interface and navigation menu across all screens so the platform is easy to use.
**Priority:** Must
**Related User Story:** US-13
**Acceptance Criteria:** Given a user moves between pages, when they use the navigation, then layouts and menus remain consistent.
**Wireframe Screen:** All screens (shared nav component)

---

### FR-14 — Mobile Responsiveness
**Description:** The system should adapt its layout for mobile devices so students can book tutoring sessions from any device.
**Priority:** Should
**Related User Story:** US-14
**Acceptance Criteria:** Given a user accesses the site on a mobile device, when the page loads, then the layout adjusts correctly.
**Wireframe Screen:** All screens (responsive behavior, not a separate screen)

---

### FR-15 — Data Privacy
**Description:** The system shall protect user personal information and display only what is necessary so student and tutor privacy is respected.
**Priority:** Must
**Related User Story:** US-15
**Acceptance Criteria:** Given user data is displayed, when a profile is viewed, then only necessary information is shown.
**Wireframe Screen:** detail-view.png (contact info handling)

---

### FR-16 — Requirement Traceability
**Description:** The system shall ensure every screen and feature in the prototype maps back to a functional requirement and user story, so the deliverable can be verified against Lab 04 and Lab 05 documentation.
**Priority:** Must
**Related User Story:** US-16
**Acceptance Criteria:** Given the prototype is reviewed, when requirements are checked, then every feature maps to a requirement and user story.
**Wireframe Screen:** All screens (traceability, not a distinct screen)

---

## Requirement Traceability Matrix

| Requirement | User Story | Wireframe Screen | Priority |
|---|---|---|---|
| FR-01 | US-01 | homepage.png | Must |
| FR-02 | US-02 | (flow across screens) | Must |
| FR-03 | US-03 | input-form.png | Must |
| FR-04 | US-04 | N/A (data layer) | Must |
| FR-05 | US-05 | record-list.png / dashboard.png | Must |
| FR-06 | US-06 | record-list.png | Must |
| FR-07 | US-07 | detail-view.png | Must |
| FR-08 | US-08 | dashboard.png / admin-view.png | Must |
| FR-09 | US-09 | admin-view.png | Must |
| FR-10 | US-10 | input-form.png | Must |
| FR-11 | US-11 | input-form.png | Must |
| FR-12 | US-12 | dashboard.png | Must |
| FR-13 | US-13 | All screens | Must |
| FR-14 | US-14 | All screens | Should |
| FR-15 | US-15 | detail-view.png | Must |
| FR-16 | US-16 | All screens | Must |

---

## Out of Scope for MVP (Future Requirements)

| ID | Feature | Reason for Postponing |
|---|---|---|
| FUT-01 | Online payment | Outside MVP scope |
| FUT-02 | Real-time chat | Requires additional backend services |
| FUT-03 | Tutor ratings and reviews | Not required for first prototype |
| FUT-04 | Email/SMS notifications | Requires third-party APIs |

---

## Authors
**ICT105 Team 2**
**Project:** Peer Tutoring Booking Platform
**Lab:** Lab 05 — System Requirements
