# MVP Experiment Plan

## 1. Group and Project Information

| Item | Details |
|------|---------|
| **Group Name** | Team 2 |
| **Project Title** | Peer Tutoring Booking Platform |
| **Repository Link** | https://github.com/minhtetnaing019/ict105-team2-MVP |
| **Main Target User** | Undergraduate students searching for a peer tutor |
| **Prototype Platform** | Frontend (HTML/CSS/JavaScript) with JSON/localStorage data layer |

---

## 2. Experiment Objective

The purpose of this experiment is to evaluate whether undergraduate students can successfully complete the main tutoring workflow without assistance.

The workflow includes:

- Searching for a tutor by subject
- Viewing tutor information and availability
- Submitting a booking request
- Receiving booking confirmation
- Checking booking status

---

## 3. Requirement Scope for the Experiment

| Requirement ID | Requirement Summary | Screen / Feature | Included |
|----------------|---------------------|------------------|----------|
| FR-01 | Homepage / Landing Screen | `homepage.html` | ✅ Yes |
| FR-03 | Booking Form Submission | `input-form.html` | ✅ Yes |
| FR-06 | Search Tutor by Subject | `record-list.html` | ✅ Yes |
| FR-07 | Tutor Detail View | `detail-view.html` | ✅ Yes |
| FR-08 | Booking Status Tracking | `dashboard.html` | ✅ Yes |
| FR-09 | Admin Management | `admin-view.html` | ❌ No |
| FR-10 | Form Validation | `input-form.html` | ✅ Yes |
| FR-11 | Booking Confirmation | `input-form.html` | ✅ Yes |

---

## 4. MVP Experiment Type

### Available Experiment Types

- Clickable Prototype
- Landing Page Test
- Form-based Simulation
- Dashboard Demo
- Manual Service Simulation
- **Simple Web Prototype**
- Backend / Database Prototype

### Selected Experiment Type

**Simple Web Prototype**

### Reason

The team selected a simple web prototype because it allows participants to complete the full tutoring process:

1. Search for tutors
2. View tutor profiles
3. Submit a booking request
4. Receive confirmation
5. Track booking status

Unlike a static prototype, the HTML/CSS/JavaScript implementation demonstrates form validation, page navigation, and sample data interaction using JSON and localStorage. This also aligns with the technical architecture prepared in Lab 06.

---

## 5. Test Users

| User Group | Number | Reason |
|------------|--------|--------|
| Undergraduate Students (Tutee) | 4 | Primary users who will search for and book tutors |
| Undergraduate Students (Peer Tutor) | 1 | Reviews tutor profile information and availability details |

**Total Testers:** **5**

---

## 6. Experiment Procedure

Each usability testing session follows these steps:

1. Introduce the project and explain the purpose of the experiment.
2. Ask the participant to perform the five tasks listed in `experiment-script.md`.
3. Encourage the participant to think aloud while completing each task.
4. Observe and record:
   - Task completion
   - Completion time
   - Errors
   - Hesitation
   - Confusing screens
5. Record observations using:

   - `data/experiment-results-template.csv`

6. After completing the tasks, ask the participant to complete the feedback form:

   - `docs/feedback-form.md`
   - `data/feedback-form-template.csv`

Each session is conducted individually (face-to-face or online) and lasts approximately **10–15 minutes**.

---

## 7. Expected Learning

The experiment will help determine whether the current MVP design supports an understandable and efficient booking process.

Based on the collected results, the team will decide whether to:

- Continue developing the final prototype without major changes if the success metrics are achieved.
- Improve interface wording, booking status labels, or form fields if users experience confusion.
- Revise requirements or user stories if participants cannot complete the core workflow successfully.

The findings will guide the next iteration of the prototype before the final project submission.
