# Lab 08 - Customer Validation Summary

## 1. Project Title

Peer Tutoring Booking Platform

## 2. Prototype Tested

-   **Prototype version:** v0.1 (frontend HTML/CSS/JavaScript prototype,
    `prototype/Prototype.html`)
-   **Prototype link or screenshot location:**
    `prototype/mvp-demo-link.md`,
    `/screenshots/validation-test-screens.png`
-   **Main task tested:** Submit a booking request (with status check as
    a secondary task)
-   **Related requirements:** FR-01, FR-03, FR-06, FR-07, FR-08, FR-10,
    FR-11

## 3. Test Users

  -----------------------------------------------------------------------
  Test User ID            User Role               Why this user is
                                                  relevant
  ----------------------- ----------------------- -----------------------
  TU-01                   Student, Year 2 (Tutee) Primary target user who
                                                  has needed a tutor
                                                  before

  TU-02                   Student, Year 3         Represents the tutor
                          (Informal Tutor)        side of the marketplace

  TU-03                   Student, Year 1         Needs clear
                          International Student   instructions as a new
                                                  user

  TU-04                   Student, Year 4         Tests first-time
                                                  usability with no
                                                  tutoring experience

  TU-05                   Student, Year 2 (Tutee) Primary target user
  -----------------------------------------------------------------------

## 4. Validation Method

-   Moderated usability testing (think-aloud)
-   Date: **2026-07-13**
-   Individual in-person/online sessions
-   **5 testers**
-   Data collected: task completion, time on task, confusion points, and
    feedback ratings.

## 5. Summary of Results

  ------------------------------------------------------------------------
  Metric                                      Result Interpretation
  --------------------- ---------------------------- ---------------------
  Total test users                                 5 Small but
                                                     representative sample

  Task success rate                        80% (4/5) Most users completed
                                                     the workflow

  Average feedback                           3.6 / 5 Generally positive
  score                                              

  Average interest                           4.2 / 5 Strong intention to
  level                                              use

  Most common confusion       Form wording & booking UI wording needs
                                              status improvement
  ------------------------------------------------------------------------

## 6. Key User Comments

-   Booking confirmation was clear and reassuring.
-   Time-slot and notes fields caused hesitation.
-   Booking status labels (Pending/Approved) were confusing.
-   One tester almost missed the search bar.

## 7. Affected Requirements

  -----------------------------------------------------------------------
  Requirement             Evidence                Improvement
  ----------------------- ----------------------- -----------------------
  FR-08                   Booking status unclear  Add clearer labels,
                                                  legend, or tooltip

  FR-03                   Time-slot & notes       Add placeholders and
                          confusion               time-slot picker

  FR-06                   Search bar hard to      Increase visibility
                          notice                  
  -----------------------------------------------------------------------

## 8. Conclusion

The MVP is **partially validated**. The booking workflow is
understandable and effective, with an **80% task success rate** and
**4.2/5 user interest**. Future iterations should improve booking status
clarity and form wording before the final prototype.
