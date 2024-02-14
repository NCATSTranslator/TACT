These are the priorities for Sprint number 1, which runs from Feb 12, 2024 to March 8, 2024.
In this sprint, the Lobster build is in CI and the Pre-Lobster build (based on the Feb 6 release) is in Test.
Each priority has a list of subtasks that are to be completed within this sprint.

# Develop Pathfinder Query
## Pre-development work:
- Determine 2-3 specific use cases for a Pathfinder query that provide value to a user AND have known inputs/expected outputs. 
- Use those specific use cases as the basis for discussion. Brainstorm to identify knowns and unknowns (eg. we know TRAPI and UI changes will be needed - what else needs to be considered?)
- Identify next steps and map out what can be completed in the upcoming development cycles
- Discuss TRAPI changes and either outline a plan for those changes AND/OR set planning goals for TRAPI for Octopus Backend Development cycle
- Discuss UI changes and either outline a plan for those changes AND/OR set planning goals for upcoming development cycles

# Add Phenotypes (HPO terms) to MVP1
## Work in CI (Lobster)
- Push to CI
## Work in Test (Pre-Lobster)
- Push to Test
- Test for controversial items
- Test for child terms

# Scalability
## Work in CI (Lobster)
- Send concurrent queries (MVP1 & 2) in batches of 5, 10, 15, 20, 25, 30
## Work in Test (Pre-Lobster)
- Send concurrent queries (MVP1 & 2) in batches of 5, 10, 15, 20, 25, 30

# Treats Refactor
## Pre-Development
- ARAs review the changes needed to continue use of treats
- Document usage of "Drug" vs "Procedure" vs "Treatment" categories
- Provide edge examples in Biolink documentation for "treats" predications
- Complete the "treats" refactor source transformation spreadsheet
## Work in CI (Lobster)
- KPs implement Biolink 4.x including the refactoring of treats edges

# CQS
## Work in CI (Lobster)
- Push initial workflows (Paths A, B, E) to TEST (end of cycle) contingent on CI tests
- Hook up CI instance of CQS to ARS in CI
- Direct CQS CI tests using test assets with new Q-A pairs
- ARS CI tests using Information Radiator
- Extend CQS to support new MVP workflows
- Develop valid TRAPI queries and deposit to CQS repo
- Identify relevant tests assets and deposit to Testing Team's G-sheet/repo
- Direct CQS tests in DEV using test assets

# MultiCURIE Queries
## Pre-Development
- Determine 2-3 specific use cases for a MultiCURIE query that provide value to a user AND have known inputs/expected outputs.
- Use those specific use cases as the basis for discussion. Brainstorm to identify knowns and unknowns (eg. we know TRAPI and UI changes will be needed - what else needs to be considered?)
- Identify next steps and map out what can be completed in the upcoming development cycles
- Discuss TRAPI changes and either outline a plan for those changes AND/OR set planning goals for TRAPI for Octopus Backend Development cycle
- Discuss UI changes and either outline a plan for those changes AND/OR set planning goals for upcoming development cycles

# New Merged Scores
## Pre-Development
- Address g() and f() for ordering / confidence score ties for MVP1 and MVP2
- Clarify testing process (data, metrics, pass/fail)
- Each project specifies its benchmarks
- Make CoLab code ready for O&O tests

# Fix Failing Automated Tests
## Work in CI (Lobster)
- Add tags to the information radiator to make clear which ARAs are failing
- Pull tagged information from the radiator into a spreadsheet grouped by ARA
- Decide per-team targets (how many failing tests need to be fixed per team) based on information in the spreadsheet
- ARAs implement fixes to reach targets

# Display Full KL/AT in the UI
## Pre-Development
- Draft documentation / implementation guidance
- Outreach to KPs to collect concerns / feedback
- Outreach to ARAs / O&O about use cases and utility of current terms

# Fix TAQA issues
## Work in CI (Lobster)
- Identify 5-10 issues that can be fully resolved
- Work to resolve these issues
- Review progress at TAQA meetings
