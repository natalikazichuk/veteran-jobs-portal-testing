# VeteranJobPortal — QA Portfolio

A manual QA portfolio project based on testing of **VeteranJobPortal**, a web platform connecting veterans with employers.

**Live project:** https://veteranjobportal.pages.dev/

## QA scope

Testing covered the main user journeys for:

- Guest / public user
- Veteran
- Recruiter

Key areas:

- Registration and authentication
- Veteran profile creation and publication
- Recruiter profile and job posting
- Job search and filters
- Job application workflow
- Recruiter application management
- Contact-access workflow
- Navigation and role-based access
- UI/UX and validation
- Negative and edge-case scenarios
- Basic API/DevTools investigation where applicable

The functional requirements and acceptance criteria were taken from the project's **User Stories and Testing Scenarios** document. The project contains separate user stories for Guest, Veteran and Recruiter roles and testing scenarios for authentication, profiles, job posting, search, applications, contact access, moderation, UI/UX, performance and edge cases.

## Testing approach

I used a combination of:

- Requirements / acceptance-criteria analysis
- Functional testing
- Positive and negative testing
- Boundary-value and validation checks
- Exploratory testing
- Role-based testing
- End-to-end user journeys
- UI/UX review
- Regression-oriented retesting
- DevTools investigation
- Bug reporting with reproduction steps and expected/actual results

## Test results

### Functional testing cycle — Build 2.0

| Metric | Result |
|---|---:|
| Test checks | 90 |
| PASS | 75 |
| FAIL | 13 |
| SKIPPED | 0 |
| BLOCKED | 0 |
| PASS rate | 83.33% |
| FAIL rate | 14.44% |
| Defects documented | 12 |

These figures are taken from the functional testing checklist included in the project materials.

### Registration-focused test cycle

| Metric | Result |
|---|---:|
| Checks | 58 |
| PASS | 41 |
| FAIL | 9 |
| BLOCKED | 2 |
| SKIPPED | 6 |
| PASS rate | 70.69% |
| FAIL + BLOCKED | 18.97% |
| Defects found | 9 |

This cycle demonstrates deeper validation of registration, email and password fields, authentication and profile completion.

## Defect examples

The project contains documented defects including:

- Incorrect password visibility icon state
- Incorrect login error message
- Application visibility problem for veterans with unpublished profiles
- Ability to apply with an incomplete profile
- Missing first-login onboarding guidance
- Invalid phone-number values accepted
- Incorrect surname display in recruiter application lists
- Non-obvious navigation terminology
- Missing required-field indicators
- Missing validation/error messages
- Incorrect role-dependent button states
- Duplicate navigation actions
- Empty UI block after the footer
- Search/list consistency issue reported from DevTools investigation

See [`bug-reports/VJP_bug_report_normalized.csv`](bug-reports/VJP_bug_report_normalized.csv).

## Traceability

The portfolio connects requirements/user stories with representative tests and observed defects.

See [`traceability/requirements_to_tests.csv`](traceability/requirements_to_tests.csv).

Examples of covered requirements:

- `US-G-001` — Browse jobs without authentication
- `US-G-002` — Search and filter jobs
- `US-V-001` — Register as Veteran
- `US-V-002` — Sign in
- `US-V-003` — Create Veteran Profile
- `US-V-006` — Search Jobs
- `US-V-007` — View Job Details
- `US-V-008` — Apply to Job
- `US-R-001` — Register as Recruiter
- `US-R-004` — Create Job Posting
- `US-R-006` — View Job Applicants
- `US-R-007` — Browse Published Veteran Profiles
- `US-R-008` — Request Contact Access

## Repository structure

```text
VJP_QA_GitHub_Portfolio/
├── README.md
├── docs/
│   ├── TEST_PLAN.md
│   ├── TESTING_SUMMARY.md
│   └── QA_APPROACH.md
├── test-cases/
│   └── VJP_selected_test_cases.csv
├── bug-reports/
│   └── VJP_bug_report_normalized.csv
├── traceability/
│   └── requirements_to_tests.csv
└── evidence/
    ├── search_job_field.jpg
    ├── categories_sectors.jpg
    ├── profile_required_fields.jpg
    ├── signup_validation.jpg
    ├── dashboard_navigation.jpg
    └── vacancy_company_link.jpg
```

## Evidence

The `evidence/` folder contains selected screenshots showing real testing observations.

Screenshots were selected to demonstrate:

- Search UI
- Category/sector navigation
- Required-field indicators
- Registration validation
- Dashboard navigation
- Vacancy/company interaction

## Notes

This repository is a portfolio representation of QA work. Source spreadsheets/PDFs are retained separately as working artifacts; this repository contains a cleaned, recruiter-friendly presentation of the work.

The source materials contain some inconsistent dates/labels and duplicate bug IDs across different report sections. The portfolio files preserve the observed testing results while normalizing the presentation for GitHub.
