# Veteran ↔ Recruiter Interaction Checklist

The working checklist contains 24 cross-role scenarios.

| ID | Role | Scenario | Expected result |
|---|---|---|---|
| 1 | Veteran | Registration | Veteran account is created |
| 2 | Recruiter | Registration | Recruiter account is created |
| 3 | Both | Authorization | User enters with the correct role |
| 4 | Veteran | Recruiter functions | Access is denied |
| 5 | Recruiter | Veteran functions | Access is limited by role |
| 6 | Veteran | Create/edit profile | Data is saved correctly |
| 7 | Veteran | Required-field validation | Errors are displayed correctly |
| 8 | Recruiter | Company profile | Profile is saved |
| 9 | Recruiter | Publish vacancy | Vacancy is created successfully |
| 10 | Veteran | View vacancies | Current vacancies are shown |
| 11 | Veteran | Search/filter vacancies | Filters work correctly |
| 12 | Veteran | Apply | Application is submitted |
| 13 | Veteran | Apply without required data | Validation prevents submission |
| 14 | Recruiter | View applications | New application appears |
| 15 | Recruiter | Accept application | Status changes to Accepted |
| 16 | Recruiter | Reject application | Status changes to Rejected |
| 17 | Veteran | View application status | Status is displayed correctly |
| 18 | Both | Status synchronization | Same status is shown to both roles |
| 19 | Veteran | Application history | Submitted applications are available |
| 20 | Both | Communication | Vet ↔ Recruiter contact is available if implemented |
| 21 | Both | Notifications | Notification appears on status change |
| 22 | Both | Error messages | Errors are clear and correct |
| 23 | Both | Direct URL access | Unauthorized access is blocked |
| 24 | Both | Navigation UX | Menu labels are understandable |

## Execution evidence
The working checklist also records role-to-role scenarios around hidden Veteran profiles, applications, contact requests and application status transitions.
