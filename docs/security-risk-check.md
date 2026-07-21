# Basic Security Risk Check
## Project Title
**Peer Tutoring Booking Platform**
| Area | Risk Question | Current Status | Risk Level | Mitigation | Owner |
|---|---|---|---|---|---|
| Form input | Can incomplete or invalid data be submitted? | Partially handled — FR-10 requires validation on the booking form, but not all fields are enforced in the current prototype draft. | Medium | Add required-field and format validation to name, subject, and time-slot fields before final build. | Eaint Shwe Sin |
| Admin function | Can normal users access admin actions? | Yes, currently — the admin dashboard has no access restriction and is reachable via a normal navigation link. | High | Move admin dashboard behind a clearly separated, non-public route and label it "admin only" for the demo. | Min Myat Maung |
| Data display | Is private information visible to everyone? | No — booking records show only to the owning student and admin; tutor profiles show only academic info by design. | Low | Continue current design; re-check before adding any new fields. | Shwe Yi Htet |
| Status update | Can records be edited without control? | Yes, currently — any user reaching the admin view could change a booking's status in the prototype demo. | High | Restrict status-change controls to the admin view only; do not expose edit controls on the student dashboard. | Min Myat Maung |
| Public links | Does a public link expose data that should be private? | No shareable/public booking links exist in the current design. | Low | Continue avoiding direct-link access to individual booking records. | Min Htet Naing |
| File upload | If used, can unsafe or unrelated files be uploaded? | Not applicable — the MVP does not include file or photo upload. | Low | No action needed; revisit if a future feature adds uploads. | Eaint Shwe Sin |
## Security Decision
- **Continue with mitigation.** The two High-risk items (unrestricted admin access, uncontrolled status updates) both stem from the same root cause: the admin dashboard is not yet separated from normal user navigation. This must be fixed — by clearly separating and labelling the admin route — before the prototype is demonstrated or shared beyond the team. See Risk Register R-02.
