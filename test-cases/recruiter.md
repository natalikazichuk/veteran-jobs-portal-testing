# Recruiter Test Cases

Source workbook sheet: Recruiter Test Cases.

| TC ID | Title | Preconditions | Steps | Expected Result | Actual Result | Status |
|---|---|---|---|---|---|---|
| TC-R-001 | Open sign-up page | User not logged in | Open Sign Up page | Page loads successfully | — | — |
| TC-R-002 | Select Recruiter role | On sign-up page | Select role = Recruiter | Role is selected | — | — |
| TC-R-003 | Register with valid email/password | Valid data | Enter email + password → Submit | Account is created | — | — |
| TC-R-004 | Validate password rules | Weak password | Enter weak password | Validation error is displayed | — | — |
| TC-R-005 | Receive confirmation | Valid registration | Submit form | Success message is shown | — | — |
| TC-R-006 | Redirect to profile setup | Account created | Complete registration | Redirect to profile setup | — | — |
| TC-R-007 | Prevent role change | Logged in recruiter | Attempt to change role | Role change is blocked | — | — |
| TC-R-008 | Redirect to profile setup | First login | Open first-login flow | Profile setup opens | — | — |
| TC-R-009 | Save company name | Company profile form is open | Enter company name | Validation passes / value is saved | — | — |
| TC-R-010 | Validate required company name | Company profile form is open | Leave empty → Save | Error is displayed | — | — |
| TC-R-011 | Enter industry | Company profile form is open | Add industry | Value is saved | — | — |
| TC-R-012 | Enter company description | Company profile form is open | Add description | Value is saved | — | — |
