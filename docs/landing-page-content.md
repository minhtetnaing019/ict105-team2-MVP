# Landing Page Content

## Project Title
StudyBridge — Peer Tutoring Booking Platform

## Target User
University students who need academic support in specific subjects, especially during exam periods. Secondary audience: student peer tutors who want more visibility for the sessions they offer.

## Headline
Find a peer tutor before the material piles up.

## Subheadline
StudyBridge puts real tutor availability, subjects, and ratings in one place so students can book a session in minutes instead of searching chat groups.

## Problem Statement
Lab 03 customer discovery found that students struggle to find reliable peer tutors during exam periods because they rely on informal methods such as chat groups and asking friends — methods that are slow, unreliable, and make it hard to confirm availability. Respondents rated the problem 4/5 on severity, with the usual consequence being going into an exam unprepared or settling for a tutor they weren't confident in. Lab 08 validation (`docs/validation-results.csv`, `docs/customer-validation-summary.md`) confirmed the booking flow and status tracking resolved this for test users, though booking-status label clarity and mobile layout still needed work.

## Solution Description
StudyBridge lets a student search tutors by subject, check real availability slots, view a tutor's profile and rating, and submit a booking request through one form. The tutor and admin side lets bookings move through Pending → Approved → Completed/Closed status so both sides know where a request stands.

## Key Features

| Feature | Requirement ID | User Value | Prototype Screen/Module |
| --- | --- | --- | --- |
| Search & filter tutors by subject | FR-06 | Find a relevant tutor in seconds instead of scrolling a chat group | Find Tutors |
| Tutor profile & availability view | FR-07 | Confirm subject fit and open time slots before requesting | Tutor Profile |
| Book a session (form + validation + confirmation) | FR-03, FR-10, FR-11 | Submit a request in one form with immediate feedback | Book a Session |
| Booking status tracking | FR-08 | Know whether a request is Pending, Approved, Completed, or Closed | Dashboard, Admin |
| Student dashboard summary | FR-12 | See booking history and stats at a glance | Dashboard |

## Benefits
- Saves time: no more asking around in chat groups for who's free.
- Reduces uncertainty: real availability and status replace guesswork.
- Builds trust: tutor profiles show subjects and track record before booking.
- Works for both sides: tutors gain visibility, students gain reliable access.

## Call-to-Action
**Try the Demo** — primary CTA, links to `prototype/Prototype.html` (Find Tutors screen).

Secondary CTA: **Give Feedback** — links to the user testing / feedback form used in Lab 13.

## Responsible Data Message
This landing page and demo do not collect real personal or contact information. Sample names, IDs, and bookings are fictional placeholders (see `docs/data-handling-policy.md` and `docs/privacy-and-data-protection.md`). If a real form is later connected, only the minimum fields needed to demonstrate a booking (name, subject, date/time, optional notes) will be collected, and users will be told not to enter sensitive personal information in the notes field.
