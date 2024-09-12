This document is PROVISIONAL and will be udpated at the beginning of sprint 6 and subject to a new vote.

These are the priorities for Sprint number 6, which runs from August 26, 2024 to October 4, 2024. 

In this sprint, the builds are in these environments: 

- PROD: Fugu
- TEST: Guppy 
- CI: Hammerhead
- DEV: I

Each priority has a list of subtasks that are to be completed within this sprint.

Note that ARAs will be required to implement at least one of MCQ, Pathfinder, or LLM.

# Develop Pathfinder Query
# Hammerhead (CI) work:
- Final decision about what elements are being scored
- Develop UI.
- Create examples document
- Manual Pathfinder testing 

# Develop Set Input
## Pre-dev
- Revisit TRAPI structure
- Make TRAPI proposal for meta KG
## Hammerhead (CI):
- Implement arbitrary 1-hops
## Guppy (TEST) work:
- Flesh out UI ideas

# LLM Summarization 
## Hammerhead (CI):
- Implement a prototype UI incorporating Karthik's LLM summarization
- Karthik investigate switching from OpenAI to Open Source
- Kaiwen produces demo over a subset of papers and questions

# O&O Based grouping in the UI 
## Pre-dev
- Investigate ARA cross-scoring. 
- Try to run a cross-scoring experiment based on Test Assets.
## Hammerhead (CI):
- Implement novelty scoring for MVP 1
- Use full sugeno + novelty + euclidean merging in UI
- Convert whether score is visible to a user-option, default off

# Display Full KL/AT in the UI
## Guppy (TEST):
- Final UI implementation

# Develop Automated Tests
## Pre-Dev
- Decide on any extra information to collect via open telemetry (OTEL)
## Hammerhead (CI):
- Implement Pathfinder tests
- Implement Set input tests
- Audit OTEL implementations
- Implement scalability testing

# Fix Failing Automated Tests
## Hammerhead (CI):
- ARAs are expected to pass 60 TopAnswer tests
- ARAs are expected to pass 400 NeverShow tests

# Collect Feedback Issues
## Guppy (TEST):
- Each team must perform manual testing of the Guppy release in TEST and report issues to the Feedback repo
between Sept 13 and Sept 20, 2024
- TAQA will review and prioritize the discovered issues

# Fix Feedback issues
## Hammerhead (CI):
- Each team will fix issues they own that are labeled with Fugu, Guppy, or Hammerhead, and close the issue.

# Technical Debt
## Hammerhead (CI): 
-  Each team closes Hammerhead (or previous) debt issues

# CLEAN-UP EFFORT: Documentation 
## Pre-development

# Publications
## Development
- Version 1 complete
- Version 2 circulated
