# Lab 04 - User Persona

## Project
**Peer Tutoring Booking Platform**

---

# 1. Persona Name

**Shwe Yi**, Year 2 International Student

---

# 2. User Type

Student who regularly needs academic help in specific subjects, especially around exam periods, and wants a fast, reliable way to find and book a peer tutor.

---

# 3. Background and Context

- Shwe Yi studies full-time and spends most of the day on campus.
- She struggles most in Calculus and Statistics, and her difficulty spikes right before exams.
- When she needs help, she usually asks classmates or posts in course-specific chat groups.
- She regularly uses:
  - Smartphone
  - University email
  - Line / Discord group chats
  - Google Docs (for shared notes)

---

# 4. Goals

- Find a tutor for a specific subject quickly.
- Check a tutor's availability before reaching out.
- Book a session with minimal back-and-forth messaging.
- Know the status of her booking request without having to follow up manually.
- Walk into an exam feeling prepared, instead of settling for whichever tutor she could find in time.

---

# 5. Pain Points from Lab 03 Evidence

| Pain Point | Evidence | Explanation |
|------------|----------|-------------|
| No structured way to check tutor availability. | Lab 03 discovery summary | Students don't know when a tutor is free until they message them directly. |
| Informal networks are slow and unreliable. | Lab 03 discovery summary | Chat groups and word-of-mouth often fail or take too long, especially close to exams. |
| Tutors are willing but lack visibility. | Lab 03 discovery summary | Students who could tutor are not discoverable through any structured channel. |
| Students settle for tutors they aren't confident in. | Lab 03 discovery summary | Time pressure near exams forces students to pick whichever tutor responds first. |
| Problem recurs predictably. | Lab 03 discovery summary | The problem occurs 2-3 times per semester, concentrated around exam periods. |

---

# 6. Current Alternatives / Workarounds

| Current Alternative | Weakness / Limitation | Evidence |
|---------------------|------------------------|----------|
| Ask friends or classmates | Limited to personal network; may not know a suitable tutor | Lab 03 interviews |
| Post in class chat groups | Slow, easily buried among other messages | Lab 03 interviews |
| Word-of-mouth referrals | Unreliable, no way to confirm tutor's actual availability | Lab 03 interviews |
| Wait for a tutor to respond | No visibility into whether the tutor is even available at the needed time | Lab 03 interviews |

---

# 7. Design Implications

The system should:

- Let students search and filter tutors by subject in one place.
- Display a tutor's availability clearly before a booking is requested.
- Provide a simple booking form with validation so incomplete requests can't be submitted.
- Give the student a visible booking status (Pending, Approved, Completed, Closed) without needing to message anyone.
- Send a confirmation immediately after a booking request is submitted.
- Give tutors visibility through a profile listing, rather than depending on their own outreach.
- Protect student and tutor privacy by showing only necessary contact information.

The team should avoid:

- Complex registration flows that create friction before a student can even search.
- Features not backed by Lab 03 evidence (e.g. real-time chat, payments, ratings) at MVP stage.
- Confusing or inconsistent navigation across screens.

### Most Important MVP Need

Provide a simple platform where students can **search for a tutor by subject, check availability, and submit a booking request**, while tutors gain visibility and an admin can keep booking status accurate.

---

# Traceability to Prototype Requirements

| Requirement | How the Prototype Supports It |
|--------------|-------------------------------|
| FR-01 | Homepage introduces the Peer Tutoring Booking Platform and its purpose. |
| FR-02 | User flow: Home → Search Tutor → Tutor Detail → Book → Confirmation. |
| FR-03 | Booking request form (student name, subject, tutor, date/time, notes). |
| FR-04 | Bookings stored in a data store (JSON/localStorage, or Firebase/Supabase). |
| FR-05 | List of the student's own bookings. |
| FR-06 | Search and filter tutors by subject. |
| FR-07 | Tutor detail page showing subjects, availability, and bio. |
| FR-08 | Booking status tracking (Pending, Approved, Completed, Closed). |
| FR-09 | Admin view for updating booking status and managing tutor listings. |
| FR-10 | Required-field validation on the booking form. |
| FR-11 | Confirmation message after a successful booking. |
| FR-12 | Dashboard showing booking summary/statistics. |
| FR-13 | Consistent navigation, layout, and styling across all screens. |
| FR-14 | Responsive design for mobile and desktop. |
| FR-15 | Limited personal data collection; only necessary info shown. |
| FR-16 | Every screen and feature maps directly to the user stories and Lab 04/05 requirements. |
