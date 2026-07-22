# ICT105 Lab Project — Peer Tutoring Booking Platform

## Team
**team2** — see [`docs/team-profile.md`](docs/team-profile.md) for member roles and skills.

## Selected IT Venture Direction
Our team selected a peer tutoring booking platform. Target users are university students who need academic help in specific subjects and currently rely on word-of-mouth or informal chat group posts to find a tutor, with no structured way to check availability or book a session. We selected this idea because it is useful, feasible, and can be prototyped as a web-based tutor listing and booking system without hardware devices.

## Problem Statement
Students frequently struggle to find reliable peer tutors during exam periods. Current informal methods (chat groups, asking friends) are slow and unreliable, leading to stress and poor exam preparation. While willing tutors exist, the lack of visibility and structured discovery prevents effective matching.

## MVP Feature Scope
Four Must-Have features, all directly traceable to Lab 03 discovery evidence (see [`docs/mvp-feature-list.md`](docs/mvp-feature-list.md)):

| Feature | Problem Solved |
|---|---|
| F01: Tutor Search by Subject | Students rely on slow, informal networks to find subject-specific help |
| F02: Tutor Availability Display | No structured way to check tutor availability |
| F03: Session Booking Request | Students settle for tutors they aren't confident in due to slow, informal arrangement |
| F04: Tutor Profile Listing | Tutors are willing to tutor but lack visibility |

## Prototype
The working prototype is a self-contained HTML/CSS/JS file: [`prototype/Prototype.html`](prototype/Prototype.html). See [`prototype/mvp-demo-link.md`](prototype/mvp-demo-link.md) for how to open it and a suggested testing walkthrough. It uses browser localStorage / sample data and does not require a backend.

## Prototype Screens (Wireframes)

| Screen | Wireframe File | Related Requirements |
|---|---|---|
| Homepage / Landing | [`wireframes/homepage.png`](wireframes/homepage.png) | FR-01 |
| Tutor Listing / Search | [`wireframes/record-list.png`](wireframes/record-list.png) | FR-05, FR-06 |
| Tutor Detail | [`wireframes/detail-view.png`](wireframes/detail-view.png) | FR-07, FR-08, FR-15 |
| Booking Form | [`wireframes/input-form.png`](wireframes/input-form.png) | FR-03, FR-10, FR-11 |
| Dashboard (student bookings / summary) | [`wireframes/dashboard.png`](wireframes/dashboard.png) | FR-05, FR-08, FR-12 |
| Admin View | [`wireframes/admin-view.png`](wireframes/admin-view.png) | FR-09 |

Full spec: [`docs/wireframe-specification.md`](docs/wireframe-specification.md). Usability review checklist: [`docs/wireframe-usability-review-checklist.md`](docs/wireframe-usability-review-checklist.md).

## Diagrams
- Use case diagram: [`diagrams/use case diagram.png`](diagrams/use%20case%20diagram.png)
- User flow diagram: [`diagrams/user-flow.png`](diagrams/user-flow.png) / [`diagrams/user flow diagram.png`](diagrams/user%20flow%20diagram.png)
- System architecture diagram: [`diagrams/system architecture diagram.png`](diagrams/system%20architecture%20diagram.png)
- Responsible IT review flow: [`diagrams/responsible-it-review-flow.mmd`](diagrams/responsible-it-review-flow.mmd)

## Documentation Index (`/docs`)

**Opportunity & discovery**
- [`idea-log.md`](docs/idea-log.md) — initial brainstormed venture ideas
- [`opportunity-scan.md`](docs/opportunity-scan.md) — NUF-scored comparison of ideas
- [`selected-opportunity.md`](docs/selected-opportunity.md), [`problem notes.md`](docs/problem%20notes.md) — why Peer Tutoring was selected
- [`customer-questions.md`](docs/customer-questions.md) — discovery interview/survey questions
- [`customer-discovery-summary.md`](docs/customer-discovery-summary.md) — findings from customer discovery
- [`assumptions-evidence-table.md`](docs/assumptions-evidence-table.md) — assumptions vs. validated evidence

**Persona, requirements & MVP scope**
- [`user-persona.md`](docs/user-persona.md) — representative student persona
- [`user-stories.md`](docs/user-stories.md) — user stories with acceptance criteria + traceability matrix
- [`mvp-feature-list.md`](docs/mvp-feature-list.md) — MoSCoW-prioritized feature list
- [`system-requirements.md`](docs/system-requirements.md) — FR-01–FR-16 functional requirements

**Product concept & wireframes**
- [`product-concept.md`](docs/product-concept.md) — target users, problem, MVP/out-of-scope
- [`feature-requirement-mapping.md`](docs/feature-requirement-mapping.md) — feature ↔ requirement ↔ wireframe traceability
- [`wireframe-specification.md`](docs/wireframe-specification.md) — per-screen wireframe spec
- [`wireframe-usability-review-checklist.md`](docs/wireframe-usability-review-checklist.md)

**Business model, architecture & data**
- [`business-model-canvas.md`](docs/business-model-canvas.md)
- [`technical-architecture.md`](docs/technical-architecture.md) — selected platform: frontend + localStorage/JSON
- [`data-structure.md`](docs/data-structure.md) — Tutor / Booking / Student entities and fields
- [`feature-value-mapping.md`](docs/feature-value-mapping.md) — user value vs. business/operational value per feature
- [`case-study-brief.md`](docs/case-study-brief.md) — one-page project brief

**MVP experiment & validation**
- [`mvp-experiment-plan.md`](docs/mvp-experiment-plan.md) — experiment objective, scope, test users
- [`critical-assumptions.md`](docs/critical-assumptions.md) — riskiest assumptions and how to test them
- [`experiment-script.md`](docs/experiment-script.md) — moderated usability test tasks
- [`feedback-form.md`](docs/feedback-form.md) — post-test rating/feedback questions
- [`success-metrics.md`](docs/success-metrics.md) — target metrics and go/revise/rethink decision rules
- [`customer-validation-summary.md`](docs/customer-validation-summary.md), [`analytics-insights.md`](docs/analytics-insights.md) — validation results and insights

**Responsible IT (legal, ethical, privacy, security)**
- [`legal-ethical-checklist.md`](docs/legal-ethical-checklist.md)
- [`privacy-and-data-protection.md`](docs/privacy-and-data-protection.md)
- [`ip-and-third-party-assets.md`](docs/ip-and-third-party-assets.md)
- [`security-risk-check.md`](docs/security-risk-check.md)
- [`risk-register.md`](docs/risk-register.md)
- [`data-handling-policy.md`](docs/data-handling-policy.md)
- [`user-consent-statement.md`](docs/user-consent-statement.md)
- [`updated-requirement-note.md`](docs/updated-requirement-note.md) — proposed requirement updates pending merge into `system-requirements.md`

**Implementation**
- [`implementation-plan.md`](docs/implementation-plan.md) — sprint scope, approach, and member responsibilities for the working prototype
- [`feature-implementation-status.md`](docs/feature-implementation-status.md) — per-requirement implementation status, evidence, and outstanding fixes

**Team & progress**
- [`team-profile.md`](docs/team-profile.md) — member roles and skills
- [`weekly-logbook.md`](docs/weekly-logbook.md) — full lab-by-lab logbook

## Data (`/data`)
See [`data/README.md`](data/README.md) for the full index. Highlights:
- `tutor-booking-sample-records.csv`, `booking-status-categories.csv` — sample Tutor/Booking records and status values matching `docs/data-structure.md`
- `raw_responses.xlsx`, `nuf_evaluation.xlsx` — raw customer discovery survey data and NUF opportunity scoring
- `test-users.csv` — sample usability test participants
- `experiment-results.csv`, `feedback-form-results.csv`, `validation-results.csv` — usability test and validation results
- `data-inventory.csv`, `risk-register.csv`, `ip-asset-register.csv`, `security-review-checklist.csv` — Responsible IT review data (see corresponding docs above)

## Repository Conventions
- Each lab's deliverables live primarily under `/docs`, with supporting data in `/data`, diagrams in `/diagrams`, wireframes in `/wireframes`, screenshots in `/screenshots`, and the working prototype in `/prototype`.
- New requirements or scope changes are proposed in a dated note under `/docs` before being merged into `system-requirements.md`, so the requirements doc stays the single source of truth.
- Every feature in the prototype should trace back to a functional requirement (`system-requirements.md`) and a user story (`user-stories.md`); see `feature-implementation-status.md` for the current mapping.
- Lab-by-lab work and member contributions are logged in `docs/weekly-logbook.md` rather than in this README, so this file can stay a stable overview across labs.
