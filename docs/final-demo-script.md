# Final Demo Script

## Demo Duration
**Recommended duration:** 5–7 minutes

## 1. Opening

StudyBridge is a peer tutoring booking platform designed for university students. During exam periods, students often struggle to find reliable peer tutors because they depend on class chat groups or friends for recommendations. This process is slow, unreliable, and makes it difficult to confirm tutor availability. StudyBridge brings tutor discovery and session booking together in one simple platform.

## 2. User Scenario

A second-year university student is having difficulty understanding recursion and Big-O analysis just 12 days before the final exam. After receiving no useful responses in the class chat group, the student opens **StudyBridge** to search for an available peer tutor and book a tutoring session.

## 3. Prototype Walkthrough

| Step | Screen / Feature | What to Demonstrate | Requirement ID |
|------|------------------|---------------------|----------------|
| 1 | Homepage | Introduce the platform, target users, exam-season problem, and click **Search Tutors** | FR-01 |
| 2 | Book a Session | Submit a booking request and demonstrate validation by leaving a required field empty before completing the form | FR-03, FR-10 |
| 3 | Find Tutors | Display the tutor list loaded from sample or `localStorage` data | FR-05 |
| 4 | Search & Filter | Filter tutors by subject (for example, Chemistry) | FR-06 |
| 5 | Tutor Profile | Show the tutor's subjects, availability schedule, and rating | FR-07 |
| 6 | Admin & Status | Approve a tutor application and update a booking status | FR-08, FR-09 |
| 7 | Dashboard & Metrics | Present total bookings, upcoming sessions, and the sessions-by-subject summary | FR-11, FR-12 |

## 4. Evidence and Validation

The project is supported by user research and multiple rounds of testing:

- **Lab 03:** Customer discovery with **8 interviews** and **14 survey responses** confirmed that finding peer tutors during exam periods is a significant problem, with an average severity rating of approximately **4/5**.
- **Lab 08:** Prototype validation confirmed that users could successfully complete the search, booking, and status-tracking workflow.
- **Lab 13:** User testing with **5 participants** (4 students and 1 admin) verified the complete end-to-end process. The most common issue across Labs 07, 08, and 13 was booking status label clarity, which was resolved in the final version by adding a **status legend** (see `docs/final-improvement-list.md`, **IMP-04**).

## 5. Closing

StudyBridge transforms an informal, chat-group-based tutor search into a structured, searchable, bookable, and trackable platform. The prototype demonstrates that students can quickly find tutors, book sessions, and track their bookings while administrators can efficiently manage tutors and booking requests.

Future improvements include live deployment for real acquisition metrics, tutor ratings and reviews, and improved mobile responsiveness for the booking and admin pages (see `docs/final-reflection.md`).
