# Weekly Venture Logbook
 
## Lab 1: Lab Setup and IT Venture Repository
### What We Completed
1. Created a new GitHub repository for the team's IT venture project.
2. Added an initial README.md file describing the project and team members.
3. Made first commits and edits directly through the GitHub website to confirm the repository was set up correctly.
### What We Learned
1. How to create a new repository on GitHub and configure basic settings (name, description, visibility).
2. How to create, edit, and commit changes to files using the GitHub web interface.
3. The basic structure of a commit, including commit messages and how changes are tracked over time.
### Problems or Difficulties
1. Some team members were unfamiliar with GitHub's interface and needed time to locate where to create and edit files.
2. Uncertainty about what to include in the first commit and how detailed the README should be at this early stage.
### Evidence of Work
- GitHub repository link: https://github.com/minhtetnaing019/ict105-team2-MVP
### Decision Made This Week
The team decided on a repository naming convention and agreed that all members would have direct access to commit changes to the main branch for this early setup phase.
 
### Plan for Next Week
In Lab 2, the team will organize the repository structure into proper folders, assign initial roles for documentation versus development tasks, and begin drafting the project proposal content based on the chosen IT venture idea.
 
---
 
## Lab 02: IT Opportunity Scanning
### What We Completed
1. Brainstormed and documented six possible IT venture ideas, each with a problem area, target users, current alternative, proposed solution, and feasible technology.
2. Scored all six ideas using the NUF (New, Useful, Feasible) framework and ranked them in a comparison table.
3. Selected one idea as the team's semester project and documented it in a selected-opportunity file.
### Selected Opportunity
Peer Tutoring Booking Platform
 
### Why We Selected It
Using NUF scoring, the Peer Tutoring Booking Platform received the highest total score among the six ideas, with strong marks in usefulness and feasibility and a reasonable novelty rating, since no dedicated peer tutoring tool currently exists on campus. Unlike ideas such as the canteen status board or ride-share app, this platform does not depend on real-time accuracy from third parties, making it easier for the team to build, test, and demonstrate a working MVP within a single semester.
 
### What We Rejected
The team rejected the Canteen Menu & Queue Status Board idea. While useful in concept, its feasibility score was lowered because it depends heavily on vendors manually and consistently updating their status, which the team cannot guarantee or fully test within a semester project.
 
### What We Learned
1. How to apply the NUF framework to objectively compare multiple project ideas against each other.
2. How to identify and weigh feasibility risks that depend on external parties (such as vendors or drivers) versus risks the team can control directly.
3. How to document and justify a selected opportunity clearly enough for it to guide the rest of the semester's development work.
### Evidence of Work
- Opportunity scan file: https://github.com/minhtetnaing019/ict105-team2-MVP/blob/main/docs/opportunity-scan.md
- NUF scoring file: https://github.com/minhtetnaing019/ict105-team2-MVP/blob/main/data/nuf_evaluation%20.xlsx
- Selected opportunity file: https://github.com/minhtetnaing019/ict105-team2-MVP/blob/main/docs/selected-opportunity.md
- Commit log: https://github.com/minhtetnaing019/ict105-team2-MVP/commits/main/
### Plan for Lab 03
The team will prepare a set of customer discovery questions focused on validating demand for peer tutoring among students, identify and approach a small sample of target users (both potential tutors and students seeking tutoring), and conduct short interviews or surveys to determine whether enough students would be willing to act as tutors to make the platform viable.
 
---
 
## Lab 03: Customer Problem Discovery
 
### What We Completed
1. Wrote a structured set of customer discovery questions covering consent, recent experience, current workarounds, pain severity, and consequence.
2. Conducted short interviews and an informal survey with students who have needed academic help and students who have informally tutored others.
3. Built an assumption-evidence table to track which of the team's beliefs about the problem and users are validated, unvalidated, or still need testing.
### What We Learned About the Problem
1. The problem is recurring rather than one-off: most respondents experience it about 2-3 times per semester, concentrated around exam periods rather than spread evenly through the term.
2. The core issue is discovery and timing, not a lack of willing tutors: students who have tutored informally said they would do it more often if students could find them more easily, suggesting tutor supply may not be the main blocker.
3. Respondents rated the problem highly on severity (around 4 out of 5 on average), with the consequence usually being going into an exam unprepared or settling for a tutor they weren't confident in.
### What Evidence We Collected
- Number of respondents/interviews: 8 interviews and 14 survey responses
- Evidence file: customer_discovery_summary.md
- Key repeated pattern: students rely on informal, relationship-based methods (chat groups, asking friends) that frequently fail or take too long, especially close to exams
### What We Changed Based on Evidence
The team narrowed the problem statement to explicitly reflect the timing and frequency data collected, rather than describing the problem only in general terms. The updated statement now ties the problem directly to exam periods and includes the severity rating as supporting evidence, making it more specific and evidence-based than the original assumption-driven version from Lab 02.
 
### Problems or Difficulties
1. Not all interviews consistently asked about willingness to pay for tutoring, leaving a gap in the evidence around the platform's potential business model.
2. It was difficult to get a clear answer on how students would expect tutor quality or trust to be verified, since this concern wasn't raised proactively by respondents and had to be probed indirectly.
### Evidence of Work
- GitHub repository link: https://github.com/minhtetnaing019/ict105-team2-MVP
- Customer discovery summary: https://github.com/minhtetnaing019/ict105-team2-MVP/blob/main/docs/customer-discovery-summary.md
- Customer discovery questions: https://github.com/minhtetnaing019/ict105-team2-MVP/blob/main/docs/customer-questions.md
- Assumption-evidence table: https://github.com/minhtetnaing019/ict105-team2-MVP/blob/main/docs/assumptions-evidence-table.md
- Commit log: https://github.com/minhtetnaing019/ict105-team2-MVP/commits/main/
### Plan for Lab 04
In Lab 04, the team will define the primary customer segment based on the discovery evidence, build a representative user persona capturing goals and frustrations around finding tutoring help, and write user stories in the format "As a [user], I want [goal], so that [reason]" to guide MVP feature prioritization.
 
---
 
## Lab 04: User Personas, User Stories, and MVP Definition
 
### What We Completed
1. Wrote a representative user persona ("Shwe Yi," Year 2 International Student) capturing core goals, pain points, and current workarounds directly tied to Lab 03 evidence.
2. Defined 16 user stories in standard format ("As a [role], I want [goal], so that [benefit]"), each with acceptance criteria, related functional requirements, and priority levels.
3. Applied MoSCoW prioritization to identify four Must-Have MVP features directly traceable to Lab 03 discovery evidence.
4. Created a traceability matrix linking every user story to functional requirements and every feature to the problems identified in customer discovery.
### MVP Features Selected
All four Must-Have features are directly evidence-backed from Lab 03:
 
| Feature | Problem Solved | Lab 03 Evidence |
|---------|----------------|-----------------|
| **F01: Tutor Search by Subject** | Students cannot find tutors for specific subjects; they rely on slow, unreliable informal networks (chat groups, asking friends) | "Students rely on informal, relationship-based methods" |
| **F02: Tutor Availability Display** | No structured way to check when tutors are available | "No structured way to check availability" |
| **F03: Session Booking Request** | Students settle for tutors they aren't confident in due to slow, informal arrangement process | "Settling for a tutor they weren't confident in" |
| **F04: Tutor Profile Listing** | Tutors are willing to tutor but lack visibility to students who need help | "Tutors are willing but lack visibility" |
 
### What We Learned
1. How to translate raw discovery evidence into specific, actionable user stories with testable acceptance criteria.
2. The importance of traceability: every user story, feature, and requirement should map back to a specific piece of evidence or a deliberately documented team assumption.
3. How to use MoSCoW prioritization not as a guessing game, but as a discipline: only features directly tied to Lab 03 evidence are marked Must-Have; any feature beyond these four (ratings, messaging, payments, mobile app) is explicitly deferred because the evidence doesn't support it.
4. How to identify a minimum viable product: the four core features represent the smallest set that directly addresses the core problem statement and validates problem-solution fit.
### Key Decisions Made
1. **Scope Discipline:** The team explicitly rejected adding features like tutor ratings, real-time messaging, online payments, and exam-period highlighting, even if intuitive, because no respondent directly requested them in Lab 03. These are deferred as Should-Have or Could-Have features pending future evidence.
2. **Evidence Traceability:** Every Must-Have feature has a direct quote or specific statement from the Lab 03 summary. Should-Have and Could-Have features are either unsupported or flagged as team inference rather than customer demand.
3. **User Story Quality:** Acceptance criteria are written in Gherkin format (Given–When–Then) to ensure they are testable and observable in the final prototype.
### Problems or Difficulties
1. Resisting feature creep: the team had to actively decline several intuitive but unvalidated features (e.g., automatic matching, AI recommendations, real-time notifications) to keep the MVP scope tight.
2. Defining acceptance criteria that are concrete enough to be testable but general enough to permit different technical implementations (e.g., "tutor details are displayed" vs. specifying exact page layout).
### Evidence of Work
- GitHub repository link: https://github.com/minhtetnaing019/ict105-team2-MVP
- User persona file: https://github.com/minhtetnaing019/ict105-team2-MVP/blob/main/docs/user-persona.md
- User stories file: https://github.com/minhtetnaing019/ict105-team2-MVP/blob/main/docs/user-stories.md
- MVP feature list: https://github.com/minhtetnaing019/ict105-team2-MVP/blob/main/docs/mvp-feature-list.md
- Traceability matrix: included in user stories document
- Commit log: https://github.com/minhtetnaing019/ict105-team2-MVP/commits/main/
### What We Changed Based on Evidence
From Lab 03 to Lab 04, the team refined the problem statement and feature scope to be purely evidence-backed. Features were only included in the MVP if they directly answered a specific pain point or goal mentioned by respondents. For example, "Tutor Search by Subject" was included because respondents explicitly said they struggle to find tutors for specific subjects; "Real-Time Notifications," while valuable, was excluded because no respondent mentioned wanting instant updates.
 
### Plan for Lab 05
In Lab 05, the team will begin prototyping the MVP. The deliverable will be a clickable, functional prototype (using HTML, CSS, and JavaScript, or a low-code tool) that demonstrates all four Must-Have features. The prototype will include:
- A homepage introducing the platform
- A tutor search and filter interface (by subject)
- Tutor profile pages showing subjects and availability
- A booking request form and confirmation flow
- A page to view bookings and track status
- Basic form validation and user feedback
- An admin dashboard to view and update booking status
The prototype will be tested against each user story's acceptance criteria to ensure every feature is observable and functional.
 
---

## Lab 05 : Product Concept and UI/UX Wireframe

## What We Completed Today
- [x] Reviewed Lab 04 requirements
- [x] Defined product concept
- [x] Mapped features to requirements
- [x] Created required wireframe screens
- [x] Created user flow diagram
- [x] Built clickable prototype draft or screen navigation plan
- [x] Updated GitHub repository

## Member Contributions

| Member Name | Contribution | Evidence / Commit Link |
|---|---|---|
| Min Htet Naing (6509785) | Defined the product concept and identified core MVP features based on customer discovery evidence. | GitHub commit |
| Min Myat Maung (6807860) | Created low-fidelity wireframes for the Home, Tutor Listing, Tutor Profile, Booking, and Confirmation screens. | GitHub commit |
| Eaint Shwe Sin (6807960) | Designed the user flow diagram and planned navigation between screens for the prototype. | GitHub commit |
| Shwe Yi Htet (6609015) | Updated the GitHub repository, documented progress, and reviewed the wireframes for consistency with user stories. | GitHub commit |

## Decisions Made

| Decision | Reason | Related Requirement |
|---|---|---|
| Focus the MVP on tutor discovery and booking only. | Customer discovery showed students mainly struggle with finding available tutors quickly during exam periods. | Product concept and MVP scope |
| Include tutor profiles with subject, availability, and ratings. | Interview and survey results indicated students want reliable information before choosing a tutor. | Functional requirements |
| Keep the booking process simple with minimal steps. | A straightforward workflow improves usability and reduces booking time. | UI/UX design |
| Design the interface primarily for mobile-responsive use. | Most university students access services using their smartphones. | Wireframe and prototype design |

## Problems Found

- Determining which features should be included in the MVP while keeping the scope manageable.
- Organizing the wireframe layout so that navigation remains simple and intuitive.
- Ensuring the user flow reflects the user stories created in Lab 04.

## Next Steps Before Lab 06

- Finalize the wireframes based on team feedback.
- Improve the clickable prototype and verify screen navigation.
- Review the UI against user stories and MVP requirements.
- Continue updating the GitHub repository with the latest design files and documentation.
- Prepare presentation materials and documentation for Lab 06.

---

## Lab 06: Business Model, Technical Architecture, and Data Structure

### Group Name
team2

### Project Title
Peer Tutoring Booking Platform

### Date
2026-07-10

### What We Completed
1. Defined the business model canvas and reviewed the feature-value mapping against MVP scope.
2. Reviewed technical architecture options against the Lab 05 wireframes and assessed UI feasibility.
3. Drafted the data structure (entities, fields, status values) for the prototype.
4. Consolidated and updated Lab 06 documentation in the GitHub repository.

### Member Contributions

| Member Name | Contribution Today | GitHub Evidence / Commit / File Updated |
|---|---|---|
| Min Htet Naing | Coordinated the team's Lab 06 work and wrote the weekly logbook. | https://github.com/minhtetnaing019/ict105-team2-MVP/blob/main/docs/weekly-logbook.md |
| Min Myat Maung | Reviewed technical architecture options against wireframes and UI feasibility. | https://github.com/minhtetnaing019/ict105-team2-MVP/blob/main/docs/technical-architecture.md |
| Eaint Shwe Sin | Drafted the data structure (entities, fields, status values) for the prototype and reviewed the feature-value mapping. | https://github.com/minhtetnaing019/ict105-team2-MVP/blob/main/docs/data-structure.md, https://github.com/minhtetnaing019/ict105-team2-MVP/blob/main/docs/feature-value-mapping.md |
| Shwe Yi Htet | Built the business model canvas and case study brief, and updated/consolidated the GitHub repository documentation for Lab 06. | https://github.com/minhtetnaing019/ict105-team2-MVP/blob/main/docs/business-model-canvas.md, https://github.com/minhtetnaing019/ict105-team2-MVP/blob/main/docs/case-study-brief.md |

### Decisions Made Today
1. **Business model decision:** The platform will remain a free, non-commercial prototype sustained by operational/institutional value (faster tutor discovery) rather than a revenue model, consistent with the Lab 04 MVP scope decision.
2. **Technical architecture decision:** Build a frontend-only prototype (HTML/CSS/JavaScript) backed by a JSON file or `localStorage`, since it covers all four Must-Have features without requiring hosted backend infrastructure.
3. **Data structure decision:** Defined three core entities — Tutor, Booking, and Student — with booking status values of Pending, Approved, Completed, and Closed.
4. **Diagram decision:** No new diagrams were required this week; existing use case and user flow diagrams from Lab 05 remain accurate for the current MVP scope.

### Problems or Risks Found
- A frontend-only data layer (`localStorage`) does not sync across devices/browsers, which could make a live demo of the student-to-admin booking flow look disconnected. Mitigation is documented in `technical-architecture.md`.
- The exact conflict-handling rules for booking requests (e.g. two students requesting the same time slot) are not yet defined and need to be resolved before the booking form is built.

### Evidence of Work
- GitHub repository link: https://github.com/minhtetnaing019/ict105-team2-MVP
- Business model canvas: https://github.com/minhtetnaing019/ict105-team2-MVP/blob/main/docs/business-model-canvas.md
- Case study brief: https://github.com/minhtetnaing019/ict105-team2-MVP/blob/main/docs/case-study-brief.md
- Feature-value mapping: https://github.com/minhtetnaing019/ict105-team2-MVP/blob/main/docs/feature-value-mapping.md
- Technical architecture: https://github.com/minhtetnaing019/ict105-team2-MVP/blob/main/docs/technical-architecture.md
- Data structure: https://github.com/minhtetnaing019/ict105-team2-MVP/blob/main/docs/data-structure.md
- Commit log: https://github.com/minhtetnaing019/ict105-team2-MVP/commits/main/

### Next Actions Before Lab 07
- Resolve booking conflict-handling rules and finalize form validation logic.
- Begin building the frontend prototype screens based on the Lab 05 wireframes.
- Populate `/data/` with sample tutor and booking JSON records matching the new data structure.
- Continue updating the GitHub repository with prototype progress.

### Lecturer / TA Notes
(For lecturer/TA use.)

---

## Lab 07: MVP Experiment Design

### Group Information
- Group name: team2
- Project title: Peer Tutoring Booking Platform
- Date: 2026-07-13
- Repository link: https://github.com/minhtetnaing019/ict105-team2-MVP

### What We Completed Today
- [x] Reviewed requirements, user stories, MVP features, architecture, and wireframes
- [x] Identified critical assumptions
- [x] Selected MVP experiment type
- [x] Defined test users and success metrics
- [x] Prepared experiment script and feedback form
- [x] Updated GitHub repository and README

### Member Contributions

| Member Name | Contribution | Evidence/Commit/Issue Link |
|---|---|---|
| Min Htet Naing | Defined experiment objective and requirement scope for the MVP test | https://github.com/minhtetnaing019/ict105-team2-MVP/blob/main/docs/mvp-experiment-plan.md |
| Min Myat Maung | Identified critical assumptions across usability and value proposition | https://github.com/minhtetnaing019/ict105-team2-MVP/blob/main/docs/critical-assumptions.md |
| Eaint Shwe Sin | Prepared experiment script and feedback form for testers | https://github.com/minhtetnaing019/ict105-team2-MVP/blob/main/docs/experiment-script.md, https://github.com/minhtetnaing019/ict105-team2-MVP/blob/main/docs/feedback-form.md |
| Shwe Yi Htet | Defined success metrics, recorded sample test results, updated logbook and README | https://github.com/minhtetnaing019/ict105-team2-MVP/blob/main/docs/success-metrics.md, https://github.com/minhtetnaing019/ict105-team2-MVP/blob/main/data/sample-experiment-results.csv |

### Key Decisions

| Decision | Reason | Evidence/Requirement Link |
|---|---|---|
| Run a simple web prototype test rather than a static clickable-only prototype | Need to validate the full search → book → status flow, not just screen navigation | Technical architecture (Lab 06) |
| Test with 4 tutee-role students and 1 tutor-role student | Covers both sides of the marketplace with a small, feasible sample size | mvp-experiment-plan.md |
| Use Pending/Approved/Completed/Closed as the only status set for this test | Keeps the experiment scope aligned with the current data structure (Lab 06) | data-structure.md |

### Problems and Next Action

| Problem | Next Action | Responsible Member |
|---|---|---|
| One tester (T04) could not complete the status-check task; status labels were unclear | Revise status label wording/tooltips before final prototype build | Min Myat Maung |
| Booking form's location/time-slot field was ambiguous for one tester | Redesign time-slot selection field for clarity | Eaint Shwe Sin |

### Evidence of Work
- GitHub repository link: https://github.com/minhtetnaing019/ict105-team2-MVP
- MVP experiment plan: https://github.com/minhtetnaing019/ict105-team2-MVP/blob/main/docs/mvp-experiment-plan.md
- Critical assumptions: https://github.com/minhtetnaing019/ict105-team2-MVP/blob/main/docs/critical-assumptions.md
- Experiment script: https://github.com/minhtetnaing019/ict105-team2-MVP/blob/main/docs/experiment-script.md
- Success metrics: https://github.com/minhtetnaing019/ict105-team2-MVP/blob/main/docs/success-metrics.md
- Feedback form: https://github.com/minhtetnaing019/ict105-team2-MVP/blob/main/docs/feedback-form.md
- Sample experiment results: https://github.com/minhtetnaing019/ict105-team2-MVP/blob/main/data/sample-experiment-results.csv
- Sample feedback results: https://github.com/minhtetnaing019/ict105-team2-MVP/blob/main/data/sample-feedback-form-results.csv
- Commit log: https://github.com/minhtetnaing019/ict105-team2-MVP/commits/main/

### Next Actions Before Lab 08
- Revise booking status labels and time-slot field based on tester confusion.
- Decide whether metrics meet target and proceed to implementation, per the decision rules in `success-metrics.md`.
- Begin building the final prototype incorporating fixes identified during this experiment.

### Lecturer / TA Notes
(For lecturer/TA use.)

---

## Lab 08: Customer Validation and Analytics Sheet

### Group Information
- Group name: team2
- Project title: Peer Tutoring Booking Platform
- Repository link: https://github.com/minhtetnaing019/ict105-team2-MVP
- Lab date: 2026-07-16

### Work Completed Today
- [x] Reviewed Lab 07 MVP experiment plan
- [x] Prepared validation dataset structure
- [x] Created or updated analytics sheet
- [x] Wrote customer validation summary
- [x] Wrote analytics insights
- [x] Wrote MVP decision
- [x] Updated README
- [x] Created GitHub issues for prototype improvements

### Member Contributions
| Member Name | Contribution | GitHub Evidence |
|---|---|---|
| Min Htet Naing | Reviewed Lab 07 experiment plan and consolidated validation dataset structure; wrote the weekly logbook | https://github.com/minhtetnaing019/ict105-team2-MVP/blob/main/data/validation-results.csv |
| Min Myat Maung | Calculated analytics metrics and wrote analytics insights | https://github.com/minhtetnaing019/ict105-team2-MVP/blob/main/docs/analytics-insights.md |
| Eaint Shwe Sin | Wrote the customer validation summary and test user notes | https://github.com/minhtetnaing019/ict105-team2-MVP/blob/main/docs/customer-validation-summary.md, https://github.com/minhtetnaing019/ict105-team2-MVP/blob/main/docs/test-user-notes.md |
| Shwe Yi Htet | Wrote the MVP decision, updated the README, and created GitHub issues for prototype improvements | https://github.com/minhtetnaing019/ict105-team2-MVP/blob/main/docs/mvp-decision.md |

### Problems Found
- The Lab 07 raw data was recorded per-task rather than per-tester, so the team had to consolidate multiple task rows per tester into a single validation row (one per Test User ID) to match the Lab 08 format.
- Booking status label confusion (Pending/Approved) reappeared as an issue in this round of testing, confirming it as a recurring, not one-off, usability problem.

### Next Actions
- Add a booking status legend/tooltip to the dashboard (FR-08).
- Replace the free-text time-slot field with a structured time-slot picker (FR-03).
- Add placeholder/example text to the booking notes field (FR-03).
- Increase the visual prominence of the tutor search bar (FR-06).
- Begin building the final prototype incorporating these fixes.
