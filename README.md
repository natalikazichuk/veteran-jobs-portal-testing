# Veteran Jobs Portal — QA Testing Portfolio

Manual QA portfolio project for **Veteran Jobs Portal**, a web application connecting veterans with recruiters and job opportunities.

## Project
- **Application:** https://veteranjobportal.pages.dev/
- **Testing:** Manual QA
- **Primary focus:** authentication, role-based access, veteran/recruiter flows, job search, applications, contact access and UI/UX
- **Tester:** Natali Kazichuk
- **Documented environment:** Windows 10 Home 22H2; Chrome and Firefox are covered in the test evidence.

## User roles
| Role | Covered flows |
|---|---|
| Guest | Landing page, job browsing, job details, restricted actions |
| Veteran | Registration, login, profile, job search, applications, profile visibility, contact requests |
| Recruiter | Registration, company profile, job posting, applicants, veteran profiles, contact access |

## QA artifacts
- [Test Plan](docs/test-plan.md)
- [Test Summary](docs/test-summary.md)
- [Test Coverage](docs/test-coverage.md)
- [Traceability / User Stories](docs/traceability.md)
- [Guest Test Cases](test-cases/guest.md)
- [Veteran Test Cases](test-cases/veteran.md)
- [Recruiter Test Cases](test-cases/recruiter.md)
- [Smoke Tests](checklists/smoke-tests.md)
- [Veteran ↔ Recruiter Interaction Checklist](checklists/role-interaction.md)
- [Bug Report Catalog](bug-reports/README.md)
- [Source Map](docs/source-map.md)
- [QA Data](data/README.md)

## Testing approach
The source materials document smoke, functional, UI, exploratory and user-flow testing. The recorded scope includes authentication, profiles, job browsing, job applications, recruiter dashboard, job management, UI/UX and access control. Performance/load, automated testing, penetration testing and payment systems were documented as out of scope for that cycle.

## Results snapshot
One consolidated Build 2.0 test summary records **90 test cases: 75 PASS, 13 FAIL, 0 BLOCKED, 0 SKIPPED, and 12 defects**. Earlier registration-focused execution recorded **58 checks: 41 PASS, 9 FAIL, 2 BLOCKED and 6 SKIPPED**. Both snapshots are preserved because the source workbook contains iterative test runs with different dates and scopes.

## Privacy
The source workbook contained test credentials and private Google Docs/Sheets/Postman links. Those details were removed from the portfolio copy before publication. No real credentials are intentionally stored in this repository.

## Project workflow
**Requirements / User Stories → Test Cases & Checklists → Execution → Bug Reports → Summary & Coverage**

> The repository contains a curated, readable portfolio view. The full sanitized working workbook remains available as a downloadable artifact in the chat.
