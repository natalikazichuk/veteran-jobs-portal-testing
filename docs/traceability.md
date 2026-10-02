# Requirements Traceability

The working materials connect requirements/user stories to test cases and execution results.

## Authentication
- **US-AUTH**: registration, sign-in, invalid credentials, protected routes, role-based access and session persistence.
- Representative cases: TC-V-*, TC-R-*, TC-G-*, and TS-AUTH-*.

## Veteran
- **US-V-001**: Register as Veteran.
- **US-V-002**: Sign in to account.
- Additional flows: profile management, profile visibility, job search, applications and contact access.

## Recruiter
The working test set defines:
- **US-R-001** Register as Recruiter
- **US-R-002** Create Recruiter Profile
- **US-R-003** Edit Recruiter Profile
- **US-R-004** Create Job Posting
- **US-R-005** View My Job Postings
- **US-R-006** View Job Applicants
- **US-R-007** Browse Published Veteran Profiles
- **US-R-008** Request Contact Access
- **US-R-009** View Contact Information
- **US-R-010** View Dashboard Overview

## Traceability model

**User Story → Test Case / Scenario → Execution Result → Bug ID**

Example:
US-V-001 → TC-V-005 → FAIL → BUG-VJP-006

The exact mapping is retained in the source workbook where detailed execution rows contain Actual Result, Status, Priority and Bug references.
