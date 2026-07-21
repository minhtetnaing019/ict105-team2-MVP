# Risk Register

## Project Title
**Peer Tutoring Booking Platform**

| Risk ID | Category | Risk Description | Affected Feature / Requirement | Severity | Likelihood | Mitigation Action | Owner | GitHub Evidence | Status |
|---|---|---|---|---|---|---|---|---|---|
| R-01 | Privacy | Booking notes are free text and could unintentionally contain sensitive personal details shared by a student. | FR-03 Booking Form Submission | Medium | Medium | Add placeholder/help text on the notes field reminding students not to share sensitive details. | Eaint Shwe Sin | Issue #16 | Open |
| R-02 | Security | Admin dashboard is reachable from normal navigation with no access separation, so any user could change booking status. | FR-09 Admin Booking and Tutor Management | High | Medium | Separate admin dashboard into its own labelled, non-public route before demo. | Min Myat Maung | Issue #16 | Open |
| R-03 | IP | One early wireframe icon was sourced from an image search with no recorded license. | UI consistency (`wireframe-specification.md`) | Medium | Medium | Replace with a Font Awesome or other open-license icon and record the source. | Min Myat Maung | Issue #11 | In Progress |
| R-04 | Ethical | Early homepage draft copy implied tutor quality was verified, which is not true for the MVP. | FR-01 Homepage | Medium | Low | Reword homepage copy to describe booking/discovery only, not guaranteed tutor quality. | Min Htet Naing | Issue #15 | Closed |
| R-05 | Legal | NUF evaluation template is course-provided material and must be credited if the repository is shared publicly. | `data/nuf_evaluation.xlsx` | Low | Low | Add course material credit line to README. | Shwe Yi Htet | Issue #17 | Open |
| R-06 | Data Quality | Booking status label confusion (Pending vs Approved) was reported by test users in Lab 07/08, which could cause students to misunderstand their booking state. | FR-08 Booking Status Tracking | Medium | Medium | Add a status legend/tooltip to the dashboard (already tracked from Lab 08 next actions). | Eaint Shwe Sin | `docs/mvp-decision.md` | Open |

## Overall Risk Decision

The prototype is **safe to continue building**, provided the two open High/Medium priority items are addressed before the next demo:

1. Separate the admin dashboard from normal navigation (**R-02**).
2. Add guidance text to the booking notes field (**R-01**).

The remaining Low-to-Medium risks can be resolved alongside ongoing development and do not block project progress.
