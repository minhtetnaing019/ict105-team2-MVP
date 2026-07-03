# Lab 04 - User Stories and Acceptance Criteria

## Project Title
**Peer Tutoring Booking Platform**

## Project Description
The Peer Tutoring Booking Platform allows undergraduate students to find peer tutors, book tutoring sessions, and track their booking status. Tutors and administrators can manage bookings and update session information.

---

## User Story Format

**As a [user role], I want to [goal/action], so that [benefit/value].**

---

## User Stories

| Story ID | Role | User Story | Related Requirement | Priority | Acceptance Criteria | Demo Evidence |
|----------|------|------------|---------------------|----------|---------------------|---------------|
| US-01 | Student | As a student, I want to view the homepage so that I can understand the platform and start booking a tutor. | FR-01 | Must | **Given** I open the website, **when** the homepage loads, **then** I can see the project title, description, and a **Book Tutor** button. | Homepage screenshot |
| US-02 | Student | As a student, I want to book a tutoring session so that I can receive academic help. | FR-02 | Must | **Given** I select a tutor, **when** I complete the booking process, **then** my booking is created successfully. | Booking process demo |
| US-03 | Student | As a student, I want to submit my booking information so that my tutoring request is saved. | FR-03 | Must | **Given** I complete all required fields, **when** I click **Submit**, **then** the booking information is stored. | Booking form screenshot |
| US-04 | System | As the system, I want to save booking records so that they can be viewed later. | FR-04 | Must | **Given** a booking is submitted, **when** the data is saved, **then** the booking appears in storage. | Database or JSON screenshot |
| US-05 | Student | As a student, I want to view my bookings so that I can check my tutoring schedule. | FR-05 | Must | **Given** bookings exist, **when** I open **My Bookings**, **then** all bookings are displayed. | Booking list screenshot |
| US-06 | Student | As a student, I want to search tutors by subject so that I can quickly find suitable tutors. | FR-06 | Must | **Given** tutor data exists, **when** I search by subject, **then** matching tutors are displayed. | Search feature screenshot |
| US-07 | Student | As a student, I want to view tutor details so that I can choose the best tutor. | FR-07 | Must | **Given** I select a tutor, **when** I open the tutor profile, **then** detailed information is displayed. | Tutor details screenshot |
| US-08 | Student | As a student, I want to track my booking status so that I know whether my request has been approved. | FR-08 | Must | **Given** I have a booking, **when** I view it, **then** the current booking status is shown. | Status page screenshot |
| US-09 | Admin | As an administrator, I want to update booking status so that students receive accurate information. | FR-09 | Must | **Given** a booking exists, **when** I update its status, **then** the new status is saved and displayed. | Admin dashboard screenshot |
| US-10 | Student | As a student, I want the booking form to validate my input so that incomplete bookings cannot be submitted. | FR-10 | Must | **Given** required fields are empty, **when** I submit the form, **then** validation messages appear. | Validation screenshot |
| US-11 | Student | As a student, I want to receive a confirmation message after booking so that I know my booking was successful. | FR-11 | Must | **Given** my booking is successful, **when** the submission finishes, **then** a success message is displayed. | Confirmation message screenshot |
| US-12 | Admin | As an administrator, I want to view a dashboard so that I can monitor booking statistics. | FR-12 | Must | **Given** booking data exists, **when** I open the dashboard, **then** summary information is displayed. | Dashboard screenshot |
| US-13 | User | As a user, I want a consistent interface so that the system is easy to navigate. | FR-13 | Must | **Given** I move between pages, **when** I use the navigation, **then** layouts and menus remain consistent. | Multiple page screenshots |
| US-14 | Student | As a student, I want the website to work on mobile devices so that I can book tutoring anywhere. | FR-14 | Should | **Given** I use a mobile device, **when** I open the website, **then** the layout adjusts correctly. | Mobile responsive screenshot |
| US-15 | Student | As a student, I want my personal information protected so that my privacy is respected. | FR-15 | Must | **Given** user data is displayed, **when** I view my profile, **then** only necessary information is shown. | Privacy feature screenshot |
| US-16 | Project Team | As a project team, I want every feature linked to project requirements so that the prototype meets assessment requirements. | FR-16 | Must | **Given** the prototype is reviewed, **when** requirements are checked, **then** every feature maps to a requirement and user story. | Traceability document |

---

## Acceptance Criteria Checklist

A good acceptance criterion should be:

- Testable
- Observable in the final prototype
- Connected to a functional requirement
- Supported by demo evidence
- Clear and specific

---

## Rejected / Future User Stories

| Story ID | Reason for Postponing | Future Condition |
|----------|-----------------------|------------------|
| FUT-01 | Online payment is outside the MVP scope. | Add after MVP completion. |
| FUT-02 | Real-time chat requires additional backend services. | Add in Version 2. |
| FUT-03 | Tutor ratings and reviews are not required for the first prototype. | Add after user testing. |
| FUT-04 | Email and SMS notifications require third-party APIs. | Implement in a future release. |

---

## Requirement Traceability Matrix

| Requirement | User Story |
|-------------|------------|
| FR-01 | US-01 |
| FR-02 | US-02 |
| FR-03 | US-03 |
| FR-04 | US-04 |
| FR-05 | US-05 |
| FR-06 | US-06 |
| FR-07 | US-07 |
| FR-08 | US-08 |
| FR-09 | US-09 |
| FR-10 | US-10 |
| FR-11 | US-11 |
| FR-12 | US-12 |
| FR-13 | US-13 |
| FR-14 | US-14 |
| FR-15 | US-15 |
| FR-16 | US-16 |

---

## Authors

**ICT105 Team 2**

**Project:** Peer Tutoring Booking Platform

**Lab:** Lab 04 - User Stories and Acceptance Criteria
