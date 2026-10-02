# Open / Follow-up QA Items

## Search suggestions / categories
A screenshot from the current testing evidence shows a partial value entered in the job-search field without a visible dropdown suggestion list.

This observation is NOT added as BUG-VJP-024 because the supplied source Bug Report currently ends at BUG-VJP-023 and the requirements do not explicitly state that autocomplete/dropdown suggestions are required.

Recommended QA action:
1. Confirm product requirement for autocomplete/suggestions.
2. If required, add a dedicated test case.
3. Reproduce on the current build.
4. Record the defect only after confirmation.

## Sector terminology
The source bug report already contains a documented UX issue for the label «Переглянути всі сектори». It is retained as BUG-VJP-010 in the normalized portfolio report.

## Source consistency
The supplied working files contain repeated bug IDs, some missing severity/priority values, different dates, and both production and stage URLs. The portfolio presentation normalizes formatting but does not invent missing test results.