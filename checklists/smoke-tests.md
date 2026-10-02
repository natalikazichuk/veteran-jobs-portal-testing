# Smoke Test Suite

Core smoke scenarios documented in the workbook:

| ID | Area | Expected result |
|---|---|---|
| SMOKE-001 | Public access / View Jobs | Jobs visible; no authentication required |
| SMOKE-002 | Veteran registration | Redirect to Veteran profile setup |
| SMOKE-003 | Recruiter registration | Redirect to Recruiter profile setup |
| SMOKE-004 | User sign-in | Redirect to dashboard |
| SMOKE-005 | Veteran profile | Profile saved successfully |
| SMOKE-006 | Recruiter profile | Company profile saved |
| SMOKE-007 | Job posting | Job becomes active and visible |
| SMOKE-008 | Apply to job | Application created / pending |
| SMOKE-009 | Applicants | Applicants are listed |
| SMOKE-010 | Veteran profile publication | Profile becomes published |
| SMOKE-011 | Data loading | No database-related UI errors |
| SMOKE-012 | Auth persistence | Session persists after refresh |
| SMOKE-013 | Protected routes | Unauthenticated user redirected to login |
| SMOKE-014 | Role access | Wrong-role dashboard is denied |
| SMOKE-015 | Basic search | Search filters job results |
