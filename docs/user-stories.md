# Lab 04 - User Stories and Acceptance Criteria

## User Story Format

**As a [user role], I want to [goal/action], so that [benefit/value].**

---

# User Stories

| Story ID | Role | User Story | Related Requirement | Priority | Acceptance Criteria | Demo Evidence |
|----------|------|------------|---------------------|----------|---------------------|---------------|
| US-01 | Student | As a student, I want to register an account, so that I can use the tutoring platform. | FR-01 User Registration | Must | **Given** I am a new user, **when** I enter valid registration details and submit the form, **then** my account is created successfully and I can log in. | Screenshot of successful registration |
| US-02 | Student | As a student, I want to log in to my account, so that I can access tutoring services. | FR-02 User Login | Must | **Given** I have a registered account, **when** I enter the correct email and password, **then** I am logged into the system. | Screenshot of login success |
| US-03 | Student | As a student, I want to search for tutors by subject, so that I can find academic help easily. | FR-03 Search Tutors | Must | **Given** I am logged in, **when** I search for a subject, **then** matching tutors are displayed. | Screenshot of search results |
| US-04 | Student | As a student, I want to book a tutoring session, so that I can receive help from a tutor. | FR-04 Book Session | Must | **Given** a tutor is available, **when** I select a time and confirm the booking, **then** the booking is saved successfully. | Screenshot of booking confirmation |
| US-05 | Tutor | As a tutor, I want to create and edit my tutor profile, so that students can learn about my skills and subjects. | FR-05 Manage Tutor Profile | Should | **Given** I am logged in as a tutor, **when** I update my profile, **then** the changes are saved and displayed correctly. | Screenshot of updated tutor profile |
| US-06 | Tutor | As a tutor, I want to view my upcoming bookings, so that I can manage my tutoring schedule. | FR-06 View Bookings | Should | **Given** students have booked sessions, **when** I open my bookings page, **then** all upcoming sessions are displayed. | Screenshot of bookings page |
| US-07 | Student | As a student, I want to cancel a booking before the scheduled time, so that I can change my plans if necessary. | FR-07 Cancel Booking | Could | **Given** I have an upcoming booking, **when** I click Cancel, **then** the booking is removed and the tutor is notified. | Screenshot of cancellation |
| US-08 | Admin | As an administrator, I want to manage user accounts, so that I can maintain the platform. | FR-08 User Management | Should | **Given** I am logged in as an administrator, **when** I delete or disable a user account, **then** the system updates successfully. | Screenshot of admin dashboard |

---

# Acceptance Criteria Checklist

A good acceptance criterion should be:

- ✔ Testable
- ✔ Observable in the final prototype
- ✔ Connected to a functional requirement
- ✔ Supported by demo evidence
- ✔ Clear and specific

---

# Rejected / Future User Stories

| Story ID | Reason for Postponing | Future Condition |
|----------|-----------------------|------------------|
| US-09 | Online video calling between students and tutors requires additional backend services. | Add after the basic booking system is completed. |
| US-10 | In-app messaging requires real-time communication features. | Implement in a future version after MVP release. |
| US-11 | Online payment integration requires third-party payment gateway support. | Develop after core tutoring functions are stable. |
