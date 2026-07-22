# Lab 10 - Implementation Plan

## 1. Project Information
- **Group name:** team2
- **Project title:** Peer Tutoring Booking Platform
- **Repository link:** https://github.com/minhtetnaing019/ict105-team2-MVP
- **Selected platform/tools:** HTML, CSS, JavaScript (single self-contained `Prototype.html`)
- **Backend status:** Simulated backend (browser localStorage, no real backend)

---

## 2. Prototype Scope for Sprint 1

List the features your group will implement in Lab 10.

| Feature | Requirement ID | User Story ID | Screen/Module | Sprint 1 Status |
|---|---|---|---|---|
| Homepage / landing screen | FR-01 | US-01 | Home | In Progress |
| Tutor search/filter | FR-06 | US-06 | Find Tutors | In Progress |
| Tutor detail view | FR-07 | US-07 | Tutor Profile | In Progress |
| Booking form submission | FR-03 | US-03 | Book a Session | In Progress |
| Booking data storage | FR-04 | US-04 | Book a Session (localStorage) | In Progress |
| Booking list / status tracking | FR-05, FR-08 | US-05, US-08 | Dashboard | In Progress |
| Admin function | FR-09 | US-09 | Admin | In Progress |
| Dashboard/summary | FR-12 | US-12 | Dashboard | In Progress |

---

## 3. Implementation Approach

Explain how your prototype will be built.

- **Frontend:** Single-page HTML/CSS/JS prototype (`prototype/Prototype.html`) with six screens (Home, Find Tutors, Tutor Profile, Book a Session, Dashboard, Admin). Navigation is handled using a `showScreen()` function instead of separate page loads.
- **Data source/storage:** Sample tutor, student, and booking data based on `docs/data-structure.md`. Booking records are stored using browser localStorage without an external database.
- **Admin/status handling:** The Admin screen includes Tutor Approvals, All Users, and Bookings tabs with Approve/Reject and Edit/Delete actions. The admin interface is separated from student navigation following the Lab 09 access-separation recommendation.
- **Search/filter approach:** Users can filter tutors by subject on the Find Tutors screen before viewing tutor details.
- **Validation approach:** Required booking fields (student name, subject, tutor, date, and time) are validated before submission. Missing information displays an inline validation message.
- **Screenshots/evidence approach:** Screenshots of completed screens will be stored in the `/screenshots` folder and referenced in the weekly logbook and README.

---

## 4. Member Responsibilities

| Member | Responsibility | Evidence of Contribution |
|---|---|---|
| Min Htet Naing | Coordination, code review, and integration of screens into the single prototype file | Commits to `prototype/Prototype.html` |
| Min Myat Maung | UI/UX implementation of screen layouts and styling | Commits to `prototype/Prototype.html` (CSS sections) |
| Eaint Shwe Sin | Frontend logic for navigation, search/filter, and form validation | Commits to `prototype/Prototype.html` (JavaScript sections) |
| Shwe Yi Htet | Sample data structure and localStorage read/write logic | Commits to `prototype/Prototype.html` (data/storage sections) |

---

## 5. Risks or Blockers

- The booking form and admin actions are currently static mockups and are not yet connected to full localStorage read/write functionality. This remains the main blocker for demonstrating FR-04 end-to-end.
- The admin route still needs to be fully separated from student navigation based on the Lab 09 finding (R-02) before the next demonstration.
