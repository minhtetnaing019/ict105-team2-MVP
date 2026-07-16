# ICT105 Lab Project — Peer Tutoring Booking Platform

## Team
**team2** — see [`docs/team-profile.md`](docs/team-profile.md) for member roles and skills.

## Selected IT Venture Direction
Our team selected a peer tutoring booking platform. Target users are university students who need academic help in specific subjects and currently rely on word-of-mouth or informal chat group posts to find a tutor, with no structured way to check availability or book a session. We selected this idea because it is useful, feasible, and can be prototyped as a web-based tutor listing and booking system without hardware devices.

## Problem Statement
Students frequently struggle to find reliable peer tutors during exam periods. Current informal methods (chat groups, asking friends) are slow and unreliable, leading to stress and poor exam preparation. While willing tutors exist, the lack of visibility and structured discovery prevents effective matching. The problem occurs 2–3 times per semester, concentrated around exam periods, with respondents rating severity 4/5 on average.

## Current Status
The team has completed customer discovery (Lab 03), defined a user persona and MVP feature scope (Lab 04), produced wireframes and a product concept (Lab 05), defined the business model / technical architecture / data structure (Lab 06), and designed and ran an MVP usability experiment (Lab 07). Next: revise the prototype based on experiment findings and move into implementation.

## MVP Feature Scope
Four Must-Have features, all directly traceable to Lab 03 discovery evidence (see [`docs/mvp-feature-list.md`](docs/mvp-feature-list.md)):

| Feature | Problem Solved |
|---|---|
| F01: Tutor Search by Subject | Students rely on slow, informal networks to find subject-specific help |
| F02: Tutor Availability Display | No structured way to check tutor availability |
| F03: Session Booking Request | Students settle for tutors they aren't confident in due to slow, informal arrangement |
| F04: Tutor Profile Listing | Tutors are willing to tutor but lack visibility |

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

## Documentation Index (`/docs`)

**Opportunity & discovery (Labs 01–03)**
- [`idea-log.md`](docs/idea-log.md) — initial brainstormed venture ideas
- [`opportunity-scan.md`](docs/opportunity-scan.md) — NUF-scored comparison of ideas
- [`selected-opportunity.md`](docs/selected-opportunity.md), [`problem notes.md`](docs/problem%20notes.md) — why Peer Tutoring was selected
- [`customer-questions.md`](docs/customer-questions.md) — discovery interview/survey questions
- [`customer-discovery-summary.md`](docs/customer-discovery-summary.md) — findings from 8 interviews + 14 survey responses
- [`assumptions-evidence-table.md`](docs/assumptions-evidence-table.md) — assumptions vs. validated evidence

**Persona, requirements & MVP scope (Lab 04)**
- [`user-persona.md`](docs/user-persona.md) — representative student persona ("Shwe Yi")
- [`user-stories.md`](docs/user-stories.md) — 16 user stories with acceptance criteria + traceability matrix
- [`mvp-feature-list.md`](docs/mvp-feature-list.md) — MoSCoW-prioritized feature list
- [`system-requirements.md`](docs/system-requirements.md) — FR-01–FR-16 functional requirements

**Product concept & wireframes (Lab 05)**
- [`product-concept.md`](docs/product-concept.md) — target users, problem, MVP/out-of-scope
- [`feature-requirement-mapping.md`](docs/feature-requirement-mapping.md) — feature ↔ requirement ↔ wireframe traceability
- [`wireframe-specification.md`](docs/wireframe-specification.md) — per-screen wireframe spec
- [`wireframe-usability-review-checklist.md`](docs/wireframe-usability-review-checklist.md)

**Business model, architecture & data (Lab 06)**
- [`business-model-canvas.md`](docs/business-model-canvas.md)
- [`technical-architecture.md`](docs/technical-architecture.md) — selected platform: frontend + localStorage/JSON
- [`data-structure.md`](docs/data-structure.md) — Tutor / Booking / Student entities and fields
- [`feature-value-mapping.md`](docs/feature-value-mapping.md) — user value vs. business/operational value per feature
- [`case-study-brief.md`](docs/case-study-brief.md) — one-page project brief

**MVP experiment (Lab 07)**
- [`mvp-experiment-plan.md`](docs/mvp-experiment-plan.md) — experiment objective, scope, test users
- [`critical-assumptions.md`](docs/critical-assumptions.md) — riskiest assumptions and how to test them
- [`experiment-script.md`](docs/experiment-script.md) — moderated usability test tasks
- [`feedback-form.md`](docs/feedback-form.md) — post-test rating/feedback questions
- [`success-metrics.md`](docs/success-metrics.md) — target metrics and go/revise/rethink decision rules

**Team & progress**
- [`team-profile.md`](docs/team-profile.md) — member roles and skills
- [`weekly-logbook.md`](docs/weekly-logbook.md) — full lab-by-lab logbook (Lab 01–07)

## Data (`/data`)
- `raw_responses.xlsx`, `nuf_evaluation .xlsx` — raw customer discovery survey data and NUF opportunity scoring (Lab 02–03)
- `sample-test-users.csv` — sample Lab 07 usability test participants
- `sample-experiment-results.csv` — sample task-level usability test results
- `sample-feedback-form-results.csv` — sample post-test feedback ratings
- `experiment-results-template.csv`, `feedback-form-template.csv` — blank templates for running further tests

## Decision for Next Step
Based on Lab 07 experiment findings, the team will revise booking status labels and the time-slot field for clarity, then proceed into building the final frontend prototype (HTML/CSS/JS + JSON/localStorage) covering the four Must-Have MVP features.
