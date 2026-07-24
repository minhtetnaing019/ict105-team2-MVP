# Startup / Product Metrics

## Purpose
Defines the basic startup/product metrics added to the Peer Tutoring Booking Platform prototype in Lab 11. Metrics are calculated from the sample booking records in `data/tutor-booking-sample-records.csv` (and the equivalent localStorage records in `prototype/Prototype.html`) and are displayed in the Dashboard and Admin summary sections.

## Metrics Table

| # | Metric | Type | Definition | Current Value (Sample Data) | Where Shown |
|---|---|---|---|---|---|
| 1 | Total Bookings | Usage Metric | Total number of booking records submitted | 10 | Dashboard, Admin Summary |
| 2 | Pending Bookings | Status Metric | Number of bookings waiting for approval | 3 | Dashboard, Admin |
| 3 | Approved Bookings | Status Metric | Number of approved bookings | 3 | Dashboard, Admin |
| 4 | Completed Bookings | Status Metric | Number of completed tutoring sessions | 2 | Dashboard |
| 5 | Closed Bookings | Status Metric | Cancelled or expired bookings | 2 | Admin |
| 6 | Most Requested Subject | Category Metric | Subject with the highest booking requests | Mathematics (3) | Dashboard |
| 7 | Active Tutors | User Activity Metric | Tutors with at least one booking | 5 | Admin Summary |
| 8 | Booking Success Rate | Validation Metric | Successful booking submissions | 80% | Dashboard |
| 9 | Average Time to Session | Operational Metric | Average days between booking and session | 5 Days | Admin Summary |

---

## Calculation Notes

- Status metrics are counted from `data/tutor-booking-sample-records.csv`.
- Status values follow `data/booking-status-categories.csv`.
- Most requested subject is calculated by counting bookings per subject.
- Active tutors are counted using unique `tutor_id` values.
- Booking success rate is taken from `data/validation-results.csv`.
- Average time to session is calculated using `session_date - booking_date`.

---

## Sample Metrics Snapshot

See `data/product-metrics-summary.csv`.

---

## How Metrics Are Used

### Students
- Track booking progress.
- View overall booking statistics.
- Understand average waiting time.

### Administrators
- Monitor booking workload.
- Identify popular subjects.
- Monitor tutor demand.
- Improve tutor availability.

### Development Team
- Measure MVP performance.
- Monitor booking completion.
- Evaluate prototype readiness for future development.

---

## Traceability

**Requirements**
- FR-08 Status Tracking
- FR-12 Dashboard Summary

**User Stories**
- US-08
- US-12

**Evidence Sources**
- `data/tutor-booking-sample-records.csv`
- `data/booking-status-categories.csv`
- `data/validation-results.csv`
