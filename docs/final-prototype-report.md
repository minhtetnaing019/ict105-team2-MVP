# Final Prototype Report

## 1. Project Title

**StudyBridge — Peer Tutoring Booking Platform**

---

## 2. Group Members and Roles

| Name | Role | Main Contribution | GitHub Evidence |
|------|------|-------------------|-----------------|
| Min Htet Naing | Team Lead | Project coordination, requirements traceability, code review | `README.md`, `docs/weekly-logbook.md` |
| Min Myat Maung | UI/UX Lead | Interface design, landing page, Admin/Dashboard synchronization | `prototype/Prototype.html`, `landing-page/` |
| Eaint Shwe Sin | Frontend Developer | Booking form logic, validation, user testing | `prototype/Prototype.html`, `docs/user-testing-plan.md` |
| Shwe Yi Htet | Backend Developer | Data structure, sample data, startup metrics | `docs/data-structure.md`, `docs/startup-metrics.md` |

---

## 3. Problem Background

The StudyBridge project was selected during **Lab 02** after receiving the highest NUF score among six proposed ideas. Customer discovery conducted in **Lab 03** validated the problem: university students often struggle to find reliable peer tutors during exam periods because they rely on informal methods such as class chat groups and recommendations from friends.

Research involving **8 interviews** and **14 survey responses** showed that this problem occurs approximately **2–3 times each semester**, particularly during examination periods, with an average severity rating of **4 out of 5**.

---

## 4. Target Users

- **Primary users:** University students seeking academic support in specific subjects.
- **Secondary users:** Student peer tutors who want an easier way to advertise their availability and receive tutoring requests.

---

## 5. Evidence Summary

- **Lab 03:** Customer discovery confirmed that the main challenge is discovering available tutors at the right time rather than a shortage of tutors.
- **Labs 07–08:** MVP validation demonstrated that the search → booking → status workflow was easy to use, although users found the booking status labels unclear.
- **Lab 13:** Final testing with **5 participants** (4 students and 1 admin) confirmed the same usability issue and identified two administrator-related defects: Dashboard status synchronization and tutor approval persistence. Both were classified as **Critical** improvements.

---

## 6. Final Prototype Overview

StudyBridge is a browser-based prototype consisting of six main screens:

1. Homepage
2. Find Tutors (search and filter)
3. Tutor Profile (subjects, availability, rating)
4. Book a Session (validated booking form)
5. Dashboard (booking history and summary statistics)
6. Admin (booking management and tutor approval)

The prototype stores booking information using the browser's `localStorage`, with initial sample data imported from `data/tutor-booking-sample-records.csv`.

---

## 7. Requirement Traceability Summary

| Requirement ID | Implemented Feature / Screen | User Story ID | Evidence Source | Status |
|----------------|------------------------------|---------------|-----------------|--------|
| FR-01 | Homepage | US-01 | Lab 03 discovery | Completed |
| FR-02 | Find Tutors → Tutor Profile → Book a Session workflow | US-02 | Lab 05 wireframes | Completed |
| FR-03 | Book a Session form | US-03 | Lab 11 implementation | Completed |
| FR-04 | `localStorage` booking persistence | US-04 | Lab 11 implementation | Completed |
| FR-05 | Dashboard booking list | US-05 | Lab 11 implementation | Completed |
| FR-06 | Tutor search and filtering | US-06 | Lab 08 validation | Completed |
| FR-07 | Tutor Profile page | US-07 | Lab 05 wireframes | Completed |
| FR-08 | Booking status tracking | US-08 | Lab 13 user testing | Partially completed (status legend added; refresh fix applied) |
| FR-09 | Admin tutor and booking management | US-09 | Lab 09 review, Lab 13 testing | Partially completed (persistence fix applied; re-testing required) |
| FR-10 | Form validation | US-10 | Lab 11 implementation | Completed |
| FR-11 | Booking confirmation message | US-11 | Lab 11 implementation | Completed |
| FR-12 | Dashboard summary statistics | US-12 | Lab 11 implementation | Completed |
| FR-13 | Consistent navigation | US-13 | Lab 10 review | Completed |
| FR-14 | Mobile responsiveness | US-14 | Labs 11 & 13 testing | Partially completed |
| FR-15 | Data privacy | US-15 | Lab 09 review | Completed |
| FR-16 | Requirements traceability | US-16 | Final report | Completed |

---

## 8. Data Handling

The prototype stores booking records, including student name, subject, tutor, booking date, time slot, notes, and booking status, using the browser's `localStorage`. Tutor profiles contain subjects, availability schedules, and ratings.

All sample names, IDs, and contact information are fictional. No real personal data is collected or transmitted. Students can search for tutors, submit bookings, and view their booking history, while administrators can manage tutor approvals and booking statuses.

---

## 9. Validation and User Testing Results

Final user testing in **Lab 13** demonstrated that users could successfully complete the complete booking journey:

- Search for tutors
- View tutor profiles
- Submit a booking request
- Receive confirmation
- Track booking status

The most common usability issue across Labs **07**, **08**, and **13** was confusion over booking status labels. This was addressed by introducing a booking status legend. Two administrator-related issues—Dashboard refresh synchronization and tutor approval persistence—were identified as Critical improvements before the final submission.

---

## 10. Startup/Product Metrics

The prototype tracks nine startup metrics defined in `docs/startup-metrics.md`, including:

- Total bookings
- Pending bookings
- Approved bookings
- Completed bookings
- Closed bookings
- Most requested subject
- Active tutors
- Booking success rate
- Average time from booking to session

These metrics are displayed on the Dashboard and Admin summary panels.

---

## 11. Business Value and Venture Direction

StudyBridge is a free, non-commercial academic prototype. Its primary value is improving the efficiency of tutor discovery and providing a structured booking process instead of relying on informal chat groups.

Future development may include tutor ratings and reviews, cloud-based data storage, and a fully deployed web application that supports multiple devices and users simultaneously.

---

## 12. Limitations and Future Improvements

Current limitations include:

- Incomplete mobile responsiveness for the booking form and Admin tables
- No live deployment for collecting real acquisition metrics
- Tutor ratings and reviews remain outside the MVP scope

Future enhancements include migrating from `localStorage` to a shared backend database, supporting email or SMS booking confirmations, improving mobile usability, expanding analytics, and enabling tutor reviews after completed sessions.
