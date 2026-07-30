# User Testing Plan

## 1. Testing Objective
Confirm that a new user can search for a tutor, understand a tutor's profile, complete a booking, and check its status without help — and surface any remaining usability issues (booking-status clarity, mobile layout) before Lab 14 final submission.

## 2. Test User Profile

| User Type | Number of Testers | Why This User Type Matters |
| --- | --- | --- |
| Target user (student needing a tutor) | 4 | Primary persona from Lab 04 (`docs/user-persona.md`); the whole booking flow is built for them |
| Admin/manager role | 1 | Validates the FR-09 admin booking/tutor-approval workflow separately from the student flow |

## 3. Testing Tasks

| Task ID | User Task | Related Requirement | Success Criteria | Observation Focus |
| --- | --- | --- | --- | --- |
| T01 | Open the homepage and explain what the system is for. | FR-01 | User can explain the value proposition (find + book a peer tutor) correctly. | Confusion about who the platform is for. |
| T02 | Search for a tutor by subject and open a tutor profile. | FR-06, FR-07 | User finds a matching tutor and can describe their availability. | Search/filter usability, profile clarity. |
| T03 | Submit a new booking request. | FR-03, FR-10, FR-11 | User completes the form without major help and sees a confirmation. | Field clarity, validation messages, confirmation visibility. |
| T04 | View the booking on the Dashboard and explain its status. | FR-05, FR-08, FR-12 | User locates the booking and correctly explains what "Pending"/"Approved" means. | Status-label clarity (recurring issue since Lab 07). |
| T05 (admin) | Approve a pending tutor application and update a booking status. | FR-08, FR-09 | Admin completes both actions and confirms the change is reflected. | Admin/student route separation, persistence of changes. |

## 4. Testing Procedure
1. Introduce the test purpose: we're checking whether the booking flow and status labels are clear, not testing the tester.
2. Ask the tester to complete each task using `prototype/Prototype.html`.
3. Do not guide unless the user is stuck for more than ~30 seconds.
4. Record completion, time, comments, and problems in `data/user-testing-results-template.csv`.
5. Ask final feedback questions: What was confusing? What would you change first?

## 5. Ethical Reminder
Do not collect real personal data from testers. Use tester codes (e.g. T01–T05) instead of names, matching `data/test-users.csv`. Explain that feedback is used only for class learning and prototype improvement (see `docs/privacy-and-data-protection.md`).
