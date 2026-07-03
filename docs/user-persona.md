# Lab 04 - User Persona

> **Project Example:** Campus Lost & Found Management System

---

# 1. Persona Name

**Shwe Yi**, Year 2 International Student

---

# 2. User Type

Student who frequently loses or finds personal belongings on campus and wants a fast, reliable way to report or recover them.

---

# 3. Background and Context

- Shwe Yi studies full-time and spends most of the day on campus.
- She often moves between classrooms, the library, cafeteria, and student activity areas.
- Personal items such as water bottles, student ID cards, umbrellas, earphones, and notebooks are sometimes left behind.
- When she loses an item, she usually asks friends or checks the university's social media groups.
- She regularly uses:
  - Smartphone
  - University email
  - Facebook
  - LINE
  - Google Maps

---

# 4. Goals

- Report a lost item quickly.
- Search for found items in one place.
- Receive updates about the status of the report.
- Contact the finder safely.
- Recover lost belongings with less time and effort.

---

# 5. Pain Points from Lab 03 Evidence

| Pain Point | Evidence ID / Respondent | Explanation |
|------------|-------------------------|-------------|
| Difficult to know where to report lost items. | R1 | Students are unsure which office or person to contact. |
| Information is scattered across different social media platforms. | R2 | Users must search multiple Facebook groups and chat rooms. |
| No update after submitting a report. | R3 | Students do not know whether someone has found their item. |
| Reporting takes too much time. | R4 | Filling forms manually or visiting offices is inconvenient. |
| Duplicate posts create confusion. | R5 | The same lost item may be reported several times. |

---

# 6. Current Alternatives / Workarounds

| Current Alternative | Weakness / Limitation | Evidence |
|---------------------|----------------------|----------|
| Ask friends or classmates | Limited reach and depends on personal network | R1 |
| Post in Facebook groups | Posts are easily buried and difficult to search | R2 |
| Visit Student Affairs Office | Only available during office hours | R3 |
| Check security office | Requires physical visit and may not have updated records | R4 |
| Use LINE group chats | Information is unorganized and disappears quickly | R5 |

---

# 7. Design Implications

The system should:

- Allow users to report lost or found items within a few minutes.
- Store all reports in a centralized database.
- Provide search and filtering by category, location, date, and status.
- Display detailed information for each item.
- Allow users to track report status (Pending, Verified, Claimed, Closed).
- Send confirmation after successful submission.
- Allow administrators to verify reports and update their status.
- Prevent incomplete submissions using form validation.
- Protect user privacy by collecting only necessary information.

The team should avoid:

- Long or complicated registration processes.
- Collecting unnecessary personal information.
- Confusing navigation.
- Requiring users to contact multiple departments.

### Most Important MVP Need

Provide a simple platform where students can **submit, search, and track lost and found items efficiently**, while allowing administrators to manage reports and keep information accurate.

---

# Traceability to Prototype Requirements

| Requirement | How the Prototype Supports It |
|--------------|-------------------------------|
| FR-01 | Homepage introduces the Lost & Found System and its purpose. |
| FR-02 | User flow: Home → Report Item → Confirmation → Track Status. |
| FR-03 | Lost/Found item submission form. |
| FR-04 | Reports stored in Firebase, Airtable, Google Sheets, or JSON. |
| FR-05 | List of all reported items. |
| FR-06 | Search and filter by item name, category, location, or status. |
| FR-07 | Detail page for each lost/found item. |
| FR-08 | Status tracking (Pending, Verified, Claimed, Closed). |
| FR-09 | Admin dashboard for approving, editing, or deleting reports. |
| FR-10 | Required fields, duplicate warning, and validation messages. |
| FR-11 | Success and error notifications after submission or updates. |
| FR-12 | Dashboard showing total reports, pending cases, claimed items, and monthly summaries. |
| FR-13 | Consistent navigation, layout, buttons, and colors across all screens. |
| FR-14 | Responsive design for both desktop and mobile devices. |
| FR-15 | Limited personal data collection and masked contact information. |
| FR-16 | Every screen and feature maps directly to the user stories, MVP, and Lab 04 requirements. |
