# Business Model Canvas

## Project Title
**Peer Tutoring Booking Platform**

## 1. Customer Segments
- **Students seeking help:** Undergraduate students who need academic support in specific subjects, especially during exam periods.
- **Peer tutors:** Undergraduate students willing to tutor others informally but who currently lack a way to be discovered.
- **Admin/coordinator:** A student or staff moderator who verifies tutor listings and manages booking status.

## 2. Value Proposition
The platform solves the problem of slow, unreliable tutor discovery. Instead of relying on chat groups and word-of-mouth, students can search tutors by subject, check availability, and submit a booking request in a structured flow. Tutors gain visibility they currently lack. The core value is faster, more confident matching between students who need help and peers willing to give it, particularly around exam periods when the need is most acute.

## 3. Channels
- University class group chats and student Discord/Line groups (initial word-of-mouth distribution, ironically the same channel the platform replaces).
- Direct link shared by faculty or student representatives.
- QR code/poster near library or study areas during exam weeks.

## 4. Customer Relationships
- Self-service: students search, view tutor profiles, and book without needing direct contact with an admin.
- Booking status updates keep students informed (Pending/Approved/Completed) without requiring back-and-forth messaging.
- Admin acts as a light-touch moderator, not a middleman for every interaction.

## 5. Revenue Streams / Sustainability Logic
This is a non-commercial student prototype, not a paid product. Its sustaining value is operational and institutional:
- Reduces time students spend searching for help, particularly during high-stress exam periods.
- Gives tutors a lightweight way to be discovered, potentially increasing informal peer-tutoring activity on campus.
- Could be adopted by a student union or department as a free service, sustained by volunteer admin moderation rather than by revenue.

## 6. Key Resources
- Wireframes and UI design assets (Lab 05).
- Sample tutor and booking data for the prototype (`/data/`).
- Team skills: frontend (HTML/CSS/JS), backend/database (Python/SQL), and design (Figma).
- Free-tier hosting/tools (e.g. GitHub Pages, Firebase/Supabase free tier).

## 7. Key Activities
- Building and maintaining the tutor listing and search feature.
- Building the booking request flow and status tracking.
- Moderating tutor listings and updating booking statuses (admin function).
- Keeping documentation and prototype in sync with user stories and requirements.

## 8. Key Partners
- Student representatives or class group admins who can help distribute the platform.
- Early volunteer tutors who agree to be listed during prototype testing.
- Course instructor/TA, who is the primary "adoption" stakeholder for a class prototype.

## 9. Cost Structure
- Development time (team hours) is the dominant cost — no paid staff.
- Free-tier hosting and database (e.g. GitHub Pages, Firebase/Supabase free tier) to avoid direct costs.
- No marketing budget; distribution relies on existing student networks.
- Ongoing cost after MVP would be admin moderation time to verify tutor listings and keep booking statuses current.

## Final Note
This business model stays deliberately narrow: it only supports the four Must-Have MVP features (F01–F04) validated by Lab 03 evidence — tutor search, availability display, booking requests, and tutor profile listing. Revenue-generating ideas (payments, premium tutor placement) are explicitly out of scope, matching the "Not in MVP" decision in `mvp-feature-list.md`, since no discovery evidence supports them yet.
