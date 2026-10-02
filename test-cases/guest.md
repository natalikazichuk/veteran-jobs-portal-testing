# Guest Test Cases

Source workbook sheet: Guest Test Cases.

| TC ID | Title | Preconditions | Steps | Expected Result | Actual Result | Status | Priority |
|---|---|---|---|---|---|---|---|
| TC-G-001 | Guest can open landing page | User is not logged in | 1. Open site URL | Landing page loads successfully without errors | Landing page loads successfully | Pass | High |
| TC-G-002 | Guest can navigate to jobs listing page | User is on landing page | 1. Click Jobs section | Jobs listing page opens | Jobs listing page opens | Pass | High |
| TC-G-003 | Guest can see active job postings | Jobs exist in system | 1. Open jobs listing page | List of active jobs is displayed | List of active jobs is displayed | Pass | High |
| TC-G-004 | Guest can view job details | Jobs exist | 1. Click a job posting | Job details page opens with full information | Job details page opens with full information | Pass | High |
| TC-G-005 | Guest cannot apply without authentication | User is not logged in | 1. Open job details<br>2. Click Apply | Login/Signup prompt appears and applying is blocked | Login/Signup prompt appears | Pass | High |
| TC-G-006 | Guest is prompted to sign in when applying | User is not logged in | 1. Click Apply | Login/Signup modal or page appears | Login/Signup modal or page appears | Pass | High |
| TC-G-N-001 | Guest cannot access application form directly | User is not logged in | 1. Open apply URL manually | User is redirected to login page | User is redirected to login page | Pass | High |
| TC-G-N-002 | Guest session remains unauthenticated after refresh | User is not logged in | 1. Refresh the page | User remains not logged in | User remains not logged in | Pass | Medium |
| TC-S-001 | Search jobs by keyword | Jobs page is open | 1. Enter keyword<br>2. Press Enter | Matching job postings are displayed | — | — | High |
| TC-S-002 | Search jobs by title | Jobs exist | 1. Enter a job title | Matching jobs are displayed | — | — | High |
| TC-S-003 | Search jobs by description | Jobs exist | 1. Enter a description word | Relevant jobs are displayed | — | — | Medium |
| TC-S-004 | Search jobs by skills | Jobs exist | 1. Enter a skill keyword | Jobs containing the skill are displayed | — | — | Medium |

> Portfolio view: representative cases are shown here; the working workbook contains the larger role-specific suite.
