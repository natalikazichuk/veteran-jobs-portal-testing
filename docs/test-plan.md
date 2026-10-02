# Test Plan — Veteran Jobs Portal

## 1. Project
**Product:** Veteran Jobs Portal  
**Type:** Web application  
**Testing type:** Manual QA  
**Primary roles:** Guest, Veteran, Recruiter  
**Build referenced in the consolidated report:** 2.0

## 2. Test objectives
The source QA report defines these objectives:
- Verify the main user flows.
- Identify functional, UX and logical defects.
- Evaluate stability and usability.
- Check product readiness for use.

## 3. Scope

### In scope
- Authentication: Sign Up / Sign In
- Profile management
- Job browsing and job search
- Job applications
- Recruiter dashboard
- Job management
- UI / UX
- Access control
- Veteran ↔ Recruiter interactions
- Content moderation checks

### Out of scope
- Performance / load testing
- Automated testing
- Security penetration testing
- Payment systems

## 4. Test approach
- Smoke testing
- Functional testing
- UI testing
- Exploratory testing
- User-flow testing

## 5. Test environments
The working evidence records **Windows 10 Home 22H2** and browser-based execution in **Chrome and Firefox**. Exact browser versions are retained in the working evidence rather than duplicated here.

## 6. Main user journeys
### Guest
Browse jobs → Open job details → Attempt restricted actions → Authentication prompt.

### Veteran
Register → Sign in → Complete/edit profile → Browse/search jobs → Apply → Track application → Interact with recruiter/contact access.

### Recruiter
Register → Create company profile → Create/publish job → View applicants → Update application status → Request/view contact information.
