# VeteranJobPortal — QA Portfolio

A manual QA portfolio project based on testing of VeteranJobPortal, a web platform connecting veterans with employers.

Live project: [https://veteran.plus/]

## QA scope

Testing covered Guest/Public, Veteran and Recruiter journeys.

Key areas: registration and authentication; veteran profile creation/publication; recruiter profile and job posting; job search and filters; applications; recruiter application management; contact access; navigation and role-based access; UI/UX and validation; negative and edge cases; basic DevTools/API investigation.

The functional requirements and acceptance criteria were taken from the project's User Stories and Testing Scenarios document.

## Testing approach

- Requirements / acceptance-criteria analysis
- Functional, positive and negative testing
- Boundary-value and validation checks
- Exploratory testing
- Role-based testing
- End-to-end user journeys
- UI/UX review
- Regression-oriented retesting
- DevTools investigation
- Bug reporting with reproduction steps and expected/actual results

## Test results

| Metric | Result |
|---|---:|
| Functional checks | 90 |
| PASS | 75 |
| FAIL | 13 |
| SKIPPED | 0 |
| BLOCKED | 0 |
| PASS rate | 83.33% |
| FAIL rate | 14.44% |
| Defects documented | 12 |

Registration-focused cycle: 58 checks, 41 PASS, 9 FAIL, 6 SKIPPED, 2 BLOCKED, 70.69% PASS, 18.97% FAIL + BLOCKED, 9 defects found.

## Defect examples

Documented defects include password visibility state, invalid-password messaging, application visibility, incomplete-profile application submission, missing onboarding guidance, phone validation, applicant data display, sector terminology, required-field indicators, role-dependent CTA states, navigation issues and search/list consistency observations.

See bug-reports/VJP_bug_report_normalized.csv.

## Traceability

Requirements/user stories are linked with representative tests and observed defects.

See traceability/requirements_to_tests.csv.

Covered examples: US-G-001, US-G-002, US-V-001, US-V-002, US-V-003, US-V-006, US-V-008, US-R-001, US-R-004, US-R-006, US-R-007, US-R-008.

## Repository structure

docs/ — test plan, testing summary, QA approach and follow-up items
test-cases/ — selected test cases
bug-reports/ — normalized defect report
traceability/ — requirements-to-tests matrix

## Portfolio note

This repository is a recruiter-friendly presentation of QA work. Source materials contain some inconsistent dates/labels and duplicate bug IDs across different report sections; the portfolio normalizes presentation without inventing missing test results.
