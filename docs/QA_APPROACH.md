# QA Approach

## Requirement analysis
The project requirements define user stories with acceptance criteria for Guest, Veteran and Recruiter roles. These requirements were used as the basis for test coverage.

## Test coverage model
Requirements -> User Stories -> Acceptance Criteria -> Test Scenarios -> Test Cases / Checklist -> Execution -> PASS / FAIL / BLOCKED -> Bug Report + Evidence -> Retest / Regression

## Examples of coverage

### Registration
- Valid email
- Existing email
- Missing email
- Invalid email formats
- Password requirements
- Password confirmation
- Empty required fields
- Role selection

### Authentication
- Valid credentials
- Invalid password
- Invalid email
- Session persistence
- Role-based redirect
- Protected routes

### Veteran profile
- Required fields
- Skills
- Military experience
- Contact information
- Employment type
- Work format
- Job directions
- Profile publication

### Job search
- Keyword search
- Ukrainian / English search
- Case sensitivity
- Prefix search
- Company search
- Empty input
- Spaces
- Special characters
- Location filters

### Application workflow
- Unauthenticated apply attempt
- Valid application
- Application status
- Recruiter visibility
- Duplicate/previous application behavior

### Recruiter workflow
- Job creation
- Job publication
- Applicant list
- Candidate profile
- Application status changes
- Contact access

## Evidence standard
For a failed test: Preconditions; reproduction steps; actual result; expected result; severity/priority where recorded; screenshot or technical evidence; related user story/test case where available.