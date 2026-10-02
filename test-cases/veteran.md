# Veteran Test Cases

Source workbook sheet: Veteran Test Cases.

| US ID | TC ID | Title | Preconditions | Steps | Expected Result | Actual Result | Status | Priority |
|---|---|---|---|---|---|---|---|---|
| US-V-001 | TC-V-001 | User can open Sign-Up page | User is not logged in | 1. Open website<br>2. Click Sign Up | Sign-Up page opens successfully | — | — | High |
| US-V-001 | TC-V-002 | User can select Veteran role | Sign-Up page is open | 1. Open role selector<br>2. Choose Veteran | Veteran role is selected successfully | — | — | High |
| US-V-001 | TC-V-003 | User can enter email and password | Sign-Up page is open | 1. Enter valid email<br>2. Enter valid password | Input fields accept user data | — | — | High |
| US-V-001 | TC-V-004 | Registration succeeds with valid data | Valid credentials entered | 1. Click Register | Account is created successfully | — | — | High |
| US-V-001 | TC-V-005 | Password validation enforces rules | Sign-Up page is open | 1. Enter weak password<br>2. Click Register | Validation error message is displayed | — | — | High |
| US-V-001 | TC-V-006 | Email format validation works | Sign-Up page is open | 1. Enter invalid email | Error message is displayed | — | — | High |
| US-V-001 | TC-V-007 | User receives confirmation after registration | Registration completed | 1. Observe system message | Success confirmation is displayed | — | — | Medium |
| US-V-001 | TC-V-008 | User is redirected to profile setup | Registration completed | 1. Wait for redirect | User is redirected to Profile Setup | — | — | High |
| US-V-001 | TC-V-009 | User cannot change role after registration | User is logged in as Veteran | 1. Open profile settings | Role field is locked or not editable | — | — | High |
| US-V-001 | TC-V-010 | Duplicate email registration is blocked | Email already exists | 1. Register with existing email | Error is shown and registration is blocked | — | — | High |
| US-V-001 | TC-V-011 | Required fields validation works | Sign-Up page is open | 1. Leave required fields empty<br>2. Click Register | Required-field error messages appear | — | — | High |
| US-V-001 | TC-V-012 | Password meets minimum security rules | Sign-Up page is open | 1. Enter password below requirements | Password is rejected with validation message | — | — | High |
