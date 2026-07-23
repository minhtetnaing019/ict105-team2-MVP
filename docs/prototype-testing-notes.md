# Prototype Testing Notes — Lab 11 Sprint 2

## Purpose
Records end-to-end testing of the main user journey in `prototype/Prototype.html` after the Sprint 2 improvements (Task 5). Covers homepage → input submission → record view → search/filter → detail view → status/admin update → dashboard metrics.

## Test Environment
- **Prototype file:** `prototype/Prototype.html`
- **Browser:** Chrome (Desktop), latest version
- **Data source:** Browser `localStorage`, seeded from `data/tutor-booking-sample-records.csv`
- **Testers:** Min Htet Naing, Min Myat Maung, Eaint Shwe Sin, Shwe Yi Htet
- **Test date:** 2026-07-22

## Test Cases

| ID | Test Case | Steps | Expected Result | Actual Result | Status | Fix / Next Action |
|----|-----------|-------|-----------------|---------------|--------|-------------------|
| **TC-01** | Homepage loads and entry point works | Open `Prototype.html`; click **Book Tutor** CTA | Homepage displays title, description, and CTA; CTA navigates to **Find Tutors** | Worked as expected | ✅ Pass | None |
| **TC-02** | Full booking journey (search → profile → book → confirm) | From **Find Tutors**, filter by **Mathematics**; open a tutor profile; click **Book**; complete the form; submit | Booking form pre-fills tutor name; submission stores a new booking and displays confirmation | Worked as expected; confirmation banner appeared and Dashboard updated with the new record | ✅ Pass | None |
| **TC-03** | Booking form validation | Leave **Date** and **Time** blank; click **Submit** | Inline validation messages appear; form submission is blocked | Validation messages displayed correctly; submission prevented | ✅ Pass | None |
| **TC-04** | Booking data persists across reload | Submit a booking, then refresh the page | New booking remains visible on the Dashboard | Booking persisted correctly using `localStorage` | ✅ Pass | None |
| **TC-05** | Tutor search/filter accuracy | Filter tutor list by **Chemistry** | Only Chemistry tutors are displayed | Correct tutors shown; filter matched sample data | ✅ Pass | None |
| **TC-06** | Dashboard summary metrics update | Submit a new booking; open Dashboard | Total bookings and Pending count increase by one | Dashboard metrics updated correctly | ✅ Pass | None |
| **TC-07** | Admin status update | Open **Admin → Bookings**; change booking status from **Pending** to **Approved** | Status updates immediately and is reflected on the student Dashboard | Admin table updated, but Dashboard still displayed **Pending** until manual refresh | ❌ Fail | Trigger a live Dashboard refresh after status updates. **Owner:** Min Myat Maung |
| **TC-08** | Admin tutor approval action | Open **Admin → Tutor Approvals**; approve a pending tutor application | Approval status changes and persists | UI updated, but changes were not saved to `localStorage`; reset after reload | ❌ Fail | Connect Tutor Approval actions to `localStorage` (FR-09, Sprint 2 Partially Completed). **Owner:** Min Myat Maung |
| **TC-09** | Mobile layout check | Resize browser to **375px** width on Booking and Admin screens | Responsive layout without horizontal scrolling | Navigation and cards adjusted correctly, but booking form and admin tables overflowed | ❌ Fail | Improve responsive CSS for forms and tables (FR-14, Sprint 2 Partially Completed). **Owner:** Min Myat Maung |
| **TC-10** | Privacy placeholder text visible | Open **Book a Session** and inspect the Notes field | Placeholder warns users not to enter sensitive information | Placeholder displayed correctly | ✅ Pass | None |

## Test Summary

- **Total Test Cases:** 10
- **Passed:** 7 ✅
- **Failed:** 3 ❌

### Key Findings

- The core booking workflow (**Search → Book → Validate → Confirm → Dashboard**) functioned correctly without defects.
- All failed test cases correspond to features already marked as **Partially Completed** in `docs/feature-implementation-status.md`.
- No additional Sprint 2 defects were identified beyond the existing tracked issues.

## Next Actions Before Lab 12

1. Implement automatic Dashboard refresh after Admin booking status updates (**TC-07**).
2. Save Tutor Approval actions to `localStorage` (**TC-08**).
3. Improve responsive layouts for booking forms and admin tables on mobile devices (**TC-09**).
