# Lab 10 - Feature Implementation Status

## Purpose
Use this file to prove that your prototype implementation is connected to `system-requirements.md`.

| Req ID | Required Functionality | Prototype Screen/Module | Current Status | Evidence | Next Fix Needed |
|---|---|---|---|---|---|
| FR-01 | Homepage or landing screen | Home | Working Draft | `prototype/Prototype.html` (Home screen) | Confirm value-proposition copy against `docs/product-concept.md` |
| FR-02 | Primary user pathway | Find Tutors → Tutor Profile → Book a Session | Working Draft | `prototype/Prototype.html` (screen flow) | Confirm full click-through path in a real browser test |
| FR-03 | User input or data submission | Book a Session | Needs Fix | `prototype/Prototype.html` (Book a Session screen) | Wire the booking form to actually submit and store data |
| FR-04 | Data storage or simulated storage | Book a Session (localStorage) | Not Started | N/A | Implement localStorage read/write for booking records |
| FR-05 | View records or information list | Dashboard | Working Draft | `prototype/Prototype.html` (Dashboard screen) | Connect list to stored booking data instead of static content |
| FR-06 | Search, filter, or category function | Find Tutors | Working Draft | `prototype/Prototype.html` (Find Tutors screen) | Verify filter logic against sample tutor data |
| FR-07 | Detail view for each record | Tutor Profile | Working Draft | `prototype/Prototype.html` (Tutor Profile screen) | Confirm availability/subjects render correctly for all sample tutors |
| FR-08 | Status or progress tracking | Dashboard / Admin | Working Draft | `prototype/Prototype.html` (Dashboard, Admin screens) | Connect status labels to actual booking status field |
| FR-09 | Admin or manager function | Admin | Needs Fix | `prototype/Prototype.html` (Admin screen) | Separate admin route from student navigation (Lab 09 finding R-02) |
| FR-10 | Validation and error prevention | Book a Session | Needs Fix | `prototype/Prototype.html` (Book a Session screen) | Implement real field validation instead of static error message |
| FR-11 | Confirmation or feedback message | Book a Session | Needs Fix | `prototype/Prototype.html` (Book a Session screen) | Trigger confirmation banner only after a real successful submission |
| FR-12 | Dashboard or summary view | Dashboard | Working Draft | `prototype/Prototype.html` (Dashboard screen) | Connect summary stats to stored booking data |
| FR-13 | UI consistency | All screens | Working Draft | `prototype/Prototype.html` (shared nav bar) | Review nav/styling consistency across all six screens |
| FR-14 | Mobile-friendly/responsive design | All screens | Not Started | N/A | Add responsive layout rules for mobile widths |
| FR-15 | Privacy and responsible data handling | Book a Session, Tutor Profile | In Progress | `docs/privacy-and-data-protection.md`, `docs/data-handling-policy.md` | Add placeholder text warning against sharing sensitive info in notes field (Lab 09 finding R-01) |
| FR-16 | Final prototype traceability | All screens | In Progress | This document, `docs/system-requirements.md` | Keep this table updated as each feature moves from mockup to working logic |

## Summary

### Features working today
- FR-01 – Homepage or landing screen
- FR-02 – Primary user pathway
- FR-05 – View records or information list
- FR-06 – Search, filter, or category function
- FR-07 – Detail view for each record
- FR-08 – Status or progress tracking
- FR-12 – Dashboard or summary view
- FR-13 – UI consistency

> These features are available as static or working-draft prototype screens and are not yet connected to live data.

### Features partially working
- FR-15 – Privacy and responsible data handling
- FR-16 – Final prototype traceability

### Features not yet started
- FR-04 – Data storage or simulated storage
- FR-14 – Mobile-friendly/responsive design

### Features requiring instructor feedback
- FR-09 – Admin/student route separation
- FR-03 – Form submission logic
- FR-10 – Form validation
- FR-11 – Confirmation message after successful submission
