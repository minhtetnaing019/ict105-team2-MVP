# Updated Requirements Note

## Purpose
Use this file only if Lab 09 review requires a change to `system-requirements.md`.

| Requirement ID | Original Requirement | Proposed Update | Reason for Change | Supporting Evidence | GitHub Issue/Commit | Approved by Team? |
|---|---|---|---|---|---|---|
| FR-09 | The system shall allow administrators to update booking status and manage tutor approvals so students receive accurate information. | Add: admin functions must be presented on a separate, clearly labelled screen/route not linked from the normal student navigation. | Lab 09 security review found the admin dashboard was reachable by any user with no separation (see `risk-register.md` R-02). | `docs/security-risk-check.md`, `docs/risk-register.md` | Issue #16 | Yes |
| FR-03 | The system shall provide a form for students to submit tutoring session requests, including student name, subject, tutor selection, date, time, and notes. | Add: the notes field must display placeholder/help text advising students not to include sensitive personal information. | Lab 09 privacy review flagged the free-text notes field as a possible source of unintentional sensitive data (see `privacy-and-data-protection.md`, `risk-register.md` R-01). | `docs/privacy-and-data-protection.md`, `docs/risk-register.md` | Issue #16 | Yes |

## Rule
Do not silently change system requirements. Every change must be justified, documented, and traceable.
