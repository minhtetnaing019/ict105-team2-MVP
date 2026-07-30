# Acquisition Metrics

## Purpose
Define how the group will measure early user interest and landing page performance for StudyBridge.

## Required Metrics

| Metric ID | Metric Name | What It Measures | Formula / Counting Method | Data Source | Target / Success Criterion |
|-----------|-------------|------------------|---------------------------|-------------|----------------------------|
| M-01 | Landing page views | Number of people who opened the landing page | Count page loads (manual tally or `localStorage` counter) | Landing page / spreadsheet | At least 20 views |
| M-02 | CTA clicks | Number of users who clicked **"Try the Demo"** | CTA clicks ÷ page views | `landing-page/script.js` counter | 30% click rate |
| M-03 | Demo attempts | Number of users who opened `prototype/Prototype.html` from the landing page | Count demo button clicks | `landing-page/script.js` counter | 10 attempts |
| M-04 | Feedback responses | Number of users who completed the Lab 13 user testing tasks or feedback | Count submitted feedback rows | `data/user-testing-results-template.csv` / Google Form | 5 responses |
| M-05 | Interest conversion | Percentage of visitors who tried the demo | (Demo attempts ÷ page views) × 100 | Spreadsheet | 20% conversion |

## Interpretation

If the metrics are below the targets:

- **Under 20 views:** Share the landing page link in more class chat groups and send it directly to Lab 03 interview participants.
- **Low CTA click rate:** Improve the headline by emphasizing **"before exams"** urgency and keep the CTA button above the fold.
- **Low demo attempts compared to CTA clicks:** Verify that the demo button correctly opens `prototype/Prototype.html`, especially on mobile devices.
- **Low feedback responses:** Shorten the Lab 13 testing tasks and collect feedback during class instead of relying only on an online form.
