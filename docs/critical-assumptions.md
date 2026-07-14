# Critical Assumptions
 
## Instruction
Identify assumptions that could cause your final prototype to fail if they are wrong.
 
| Assumption ID | Category | Assumption | Related Requirement/User Story | Risk Level | Current Evidence | How to Test |
|---|---|---|---|---|---|---|
| A-01 | User Problem | Students will switch from informal chat-group search to actively using the Find Tutors search/filter, rather than defaulting back to old habits. | F01 / US-01 | High | Lab 03: informal methods rated slow/unreliable, but no evidence students will *change behavior* | Task-based usability test: ask target students to find a tutor using only the prototype, observe drop-off |
| A-02 | Value Proposition | Tutors who said they'd tutor more "if easy to find" will actually complete registration and keep their profile/availability up to date. | F04 / US-04 | High | Lab 03: self-reported willingness only, not observed behavior | Pilot tutor sign-up; measure % who complete registration and update availability weekly |
| A-03 | Usability | Students can complete the booking form (subject, date, time slot) without confusion or errors on the first attempt. | F03 / US-03 | Medium | No evidence yet — form has not been usability-tested | Moderated task test on the Book a Session screen; track completion time and errors |
| A-04 | Technical Feasibility | The availability calendar can reliably prevent double-booking when multiple students request the same slot. | F02 / US-02 | Medium | No evidence — assumed engineering solvable, not yet tested | Simulate concurrent booking requests on the same tutor/slot during prototype testing |
| A-05 | Business Logic | A star rating + admin tutor-approval step is enough to replace the trust that comes from a friend's personal recommendation. | Admin approval flow (Tutor Approvals) | Medium | Partial: Lab 03 shows trust/confidence was a stated concern, but no evidence ratings alone resolve it | Compare booking rates for newly-approved (unrated) tutors vs. rated tutors in a pilot |
| A-06 | Data Handling | Storing student/tutor emails, schedules, and booking history with basic auth is sufficient for a semester prototype (no formal privacy/compliance review needed). | Auth Service / Users Table | Low | No evidence — assumption based on academic prototype scope, not verified against course requirements | Confirm data handling expectations with course instructor before final submission |
 
## Categories
Used above:
- User problem — A-01
- Value proposition — A-02
- Usability — A-03
- Technical feasibility — A-04
- Business logic — A-05
- Data handling — A-06
