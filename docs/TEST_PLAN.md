# Test Plan — VeteranJobPortal

## 1. Objective
Verify that the core VeteranJobPortal user journeys work according to the documented user stories and acceptance criteria, with emphasis on authentication, profiles, job discovery, applications and recruiter workflows.

## 2. Scope
Guest: landing page, active jobs, search/filters, job details, public pages.

Veteran: registration, authentication, profile creation/editing, publication, job search/details, applications, application status, contact-access requests, dashboard.

Recruiter: registration, authentication, company profile, job creation/publication, job management, applicant management, published veteran profiles, contact-access requests, dashboard.

Cross-functional: form validation, required fields, error/success messages, role-based access, navigation, responsive UI, negative scenarios, edge cases, search/filter behavior, basic DevTools/API observation.

## 3. Test types
Functional; integration/workflow; system; regression; exploratory; UI/UX; negative; boundary-value; role-based authorization; end-to-end.

## 4. Test design techniques
Equivalence partitioning; boundary-value analysis; positive/negative testing; state/role-based scenarios; validation testing; error-message verification; navigation/usability checks.

## 5. Test environment
OS: Windows 10 Home 22H2; Browser: Google Chrome 144.x; Build: 2.0; Application: VeteranJobPortal; Main test URL: https://veteranjobportal.pages.dev/. A separate registration cycle also contains Firefox checks.

## 6. Entry criteria
Test environment available; application accessible; user stories/acceptance criteria available; test accounts or registration flow available; test data prepared.

## 7. Exit criteria
Planned checks executed or explicitly marked skipped/blocked; failed checks have defect records where appropriate; critical workflows exercised end-to-end; results and evidence documented.

## 8. Risks
Ambiguity around profile/application visibility; UX expectations not always explicit; third-party email confirmation may affect registration; build changes may alter behavior; some defects depend on role/profile state.

## 9. Deliverables
Test plan; functional checklist; selected test cases; bug report; requirements-to-test traceability; screenshots/evidence; testing summary.