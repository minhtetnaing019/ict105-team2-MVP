# Digital Go-to-Market Plan

## Product / Prototype Name
StudyBridge — Peer Tutoring Booking Platform

## Target Early Users
First-wave users are university students who have needed a tutor before (or tutored informally before), reached through the same class chat groups and peer networks identified in Lab 03 customer discovery. This matches the tester profile already used in `data/test-users.csv`.

## Main Value Proposition
StudyBridge helps students find and book a peer tutor by subject in minutes instead of searching chat groups, and helps tutors get discovered instead of relying on word of mouth.

## Channel Plan

| Channel | Target User | Message Angle | User Action Expected | Metric to Track | Why This Channel Fits |
| --- | --- | --- | --- | --- | --- |
| Class chat groups (Line/Discord) | Students who currently ask in chat groups for tutors | Stop scrolling chat groups — see real tutor availability in one place | Click demo link | Clicks / demo views | This is the exact workaround Lab 03 respondents described |
| Campus poster with QR code | Students on campus near exam periods | Find a tutor before the material piles up | Scan QR → open landing page | QR scans / landing page views | Places the message where the problem happens (near classrooms/library) |
| Instagram/Line story | Broader student community | Book a peer tutor in one form, no messaging back and forth | Visit landing page | Story link clicks | Familiar, low-effort channel students already use |
| Direct ask to peer tutors | Students who tutor informally (Lab 03 respondents) | Get discovered by more students needing your subject | Fill in tutor profile / try demo as a tutor | Tutor sign-up interest | Builds the supply side needed before students can book |

## Launch Sequence
1. Finalize landing page (`landing-page/`) and confirm the demo link points to `prototype/Prototype.html`.
2. Share the landing page link in the class chat groups and to the Lab 03 interview contacts first (warm audience).
3. Post the campus poster/QR and story content in the week before exams start, matching the "exam season" urgency used in the prototype homepage.
4. Track views, CTA clicks, and demo attempts using the landing page's built-in localStorage counters (see `script.js`).
5. Collect feedback via the Lab 13 user testing plan and revise headline, CTA wording, or prototype flow based on results.

## Risk and Mitigation
- **Risk:** Students click through but don't understand it's a class prototype, not a live service. **Mitigation:** Keep the "ICT105 Lab Prototype" label visible on both the landing page and prototype footer.
- **Risk:** Low tutor-side interest limits what students can book. **Mitigation:** Message peer tutors from Lab 03 discovery directly, since they already showed willingness to tutor if it were easier to be found.
- **Risk:** Mobile users bounce because the prototype isn't fully responsive yet (Lab 11 finding, FR-14 partially complete). **Mitigation:** Prioritize the mobile CSS fixes before wider distribution of the landing page link.
