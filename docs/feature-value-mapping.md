# Feature-Value Mapping

## Project Title
**Peer Tutoring Booking Platform**

---

## Feature Mapping

| Feature ID | MVP Feature | Requirement ID | User Story ID | User Value | Business / Operational Value | Prototype Screen or Module | Priority |
|-------------|-------------|----------------|---------------|------------|------------------------------|----------------------------|----------|
| **F-01** | Tutor Search by Subject | FR-06 | US-06 | Students can quickly find tutors for specific subjects without relying on informal chat groups. | Reduces time spent searching for tutors and increases visibility of available tutors. | `record-list.html` | Must |
| **F-02** | Tutor Availability Display | FR-07 | US-07 | Students can view tutor schedules before requesting a session. | Reduces booking conflicts and duplicate requests. | `detail-view.html` | Must |
| **F-03** | Session Booking Request | FR-02, FR-03, FR-10, FR-11 | US-02, US-03, US-10, US-11 | Students can submit a structured booking request with confirmation. | Creates organized booking records instead of unstructured chat messages. | `input-form.html` | Must |
| **F-04** | Tutor Profile Listing | FR-01, FR-04, FR-05, FR-08, FR-09, FR-12 | US-01, US-04, US-05, US-08, US-09, US-12 | Students can browse tutor profiles and tutors gain better visibility. | Provides administrators with a centralized view to manage tutors and bookings. | `homepage.html`, `dashboard.html`, `admin-view.html` | Must |

---

# Feature Summary

| Feature | Main User |
|---------|-----------|
| Tutor Search by Subject | Student |
| Tutor Availability Display | Student |
| Session Booking Request | Student |
| Tutor Profile Listing | Student, Tutor, Admin |

---

# Priority Summary

| Priority | Description |
|----------|-------------|
| Must | Required for the Minimum Viable Prototype (MVP). All listed features are essential for demonstrating the system. |

---

# Reflection

## 1. Which feature creates the strongest user value?

**Tutor Search by Subject (F-01)** provides the greatest value because students can immediately locate tutors who teach the subject they need. This solves the main problem identified during customer discovery, where students depended on classmates or chat groups to find academic help.

---

## 2. Which feature creates the strongest business or operational value?

**Tutor Profile Listing (F-04)** delivers the highest operational value because it provides administrators with one centralized location to manage tutor information and monitor bookings. This replaces scattered communication with an organized and maintainable system.

---

## 3. Which required feature is still weak or unclear?

**Session Booking Request (F-03)** still requires further refinement. The booking validation process, such as preventing conflicting time slots, handling unavailable tutors, and allowing booking approval or rejection, should be clearly defined during prototype development.

---

# Overall Value

The four MVP features work together to achieve the project's objectives:

- Students can search for tutors by subject.
- Students can view tutor availability before booking.
- Students can submit structured tutoring requests.
- Administrators can manage tutor profiles and booking records efficiently.

Together, these features replace informal communication with a simple, organized booking platform for peer tutoring.
