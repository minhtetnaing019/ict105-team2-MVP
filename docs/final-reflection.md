# Final Reflection

## 1. What We Built
StudyBridge is a web-based peer tutoring booking platform prototype (`prototype/Prototype.html`). It includes six screens: Home, Find Tutors, Tutor Profile, Book a Session, Dashboard, and Admin. The prototype stores data using browser `localStorage`. We also created a landing page (`landing-page/`) to support digital marketing.

## 2. What We Learned About Users
We learned that students need a faster and easier way to find tutors, especially before exams. During testing, many users were confused by the booking status labels such as **Pending** and **Approved**. This showed that adding a simple status legend or explanation improves usability.

## 3. What We Learned About Requirements
We found that some requirements were more complex than expected. For example, admin management required both data storage and page synchronization. Keeping requirements linked to user stories, prototype screens, and test cases made it easier to track improvements.

## 4. What We Improved After Testing
- Connected the booking form to `localStorage`.
- Added form validation and confirmation messages.
- Updated Dashboard statistics using live data.
- Fixed Admin and Dashboard synchronization.
- Improved mobile responsiveness.
- Added a booking status legend to reduce user confusion.

## 5. What Was Difficult Technically
The biggest challenge was keeping the Admin page and Dashboard synchronized without a real backend. We solved this by refreshing the interface after every admin update so both pages always displayed the latest data.

## 6. What We Would Improve Next
In the future, we would replace `localStorage` with a real backend such as Firebase so data can sync across devices. We would also add tutor ratings and reviews and deploy the system online to collect real user feedback and startup metrics.

## 7. Individual Contributions

| Member | Contribution | Evidence |
|--------|--------------|----------|
| Min Htet Naing | Project coordination, requirements tracking, weekly logbooks, README updates | `README.md`, `docs/weekly-logbook.md` |
| Min Myat Maung | Landing page UI, prototype interface, admin/dashboard improvements, responsive design | `landing-page/`, `prototype/Prototype.html` |
| Eaint Shwe Sin | Booking form, validation, confirmation messages, user testing | `prototype/Prototype.html`, `docs/user-testing-plan.md` |
| Shwe Yi Htet | Data structure, sample data, startup metrics, final improvement summary | `docs/data-structure.md`, `docs/startup-metrics.md`, `docs/final-improvement-list.md` |
