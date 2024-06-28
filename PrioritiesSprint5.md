This document is PROVISIONAL and will be udpated at the beginning of sprint 5 and subject to a new vote.

These are the priorities for Sprint number 5, which runs from July 22, 2024 to August 23, 2024. 

In this sprint, the builds are in these environments: 

- PROD: Eel
- TEST: Fugu 
- CI: Guppy
- DEV: Hammerhead

Each priority has a list of subtasks that are to be completed within this sprint.

Note that ARAs will be required to implement at least one of MCQ, Pathfinder, or LLM.

# Develop Pathfinder Query
## Pre-development work:
- Implement automated tests
- Establish performance goals
## Guppy (CI) work:
- Continue to improve results

# MultiCURIE Query (MCQ)
## Fugu (TEST) work:
- Develop UI.  UI must be developed in a way that the build could be pushed to PROD with or without MCQ enabled
- Manual MCQ testing once the UI is developed
- Go / No-go decision on releasing MCQ to PROD

# LLM Summarization 
## Pre-development work:
- Assess effectiveness and usefulness of each proposed approach.  Engineering and cost assessment for each approach.  Assess cost, quality, and other tradeoffs for different "open" and non-open LLMs, and determine if a model-agnostic approach is feasible.

# O&O Based grouping in the UI 
## Guppy (CI):
## Fugu (TEST):

# Display Full KL/AT in the UI
## Guppy (CI):
- Complete QA of KP implementation
## Fugu (TEST):
- Initial UI implmentation

# Develop Automated Tests
## Pre-Development
- Run Benchmarking Suite
- Run MCQ Suite

# Fix Failing Automated Tests
## Guppy (CI):
- Each ARA is expected to pass X tests from the Sprint 5 test suite

# Collect Feedback Issues
## Fugu (TEST):
- Each team must perform manual testing of the Fugu release in TEST and report issues to the Feedback repo
between July 2 and July 9, 2024
- TAQA will review and prioritize the discovered issues

# Fix Feedback issues
## Guppy (CI):
- Each team will fix issues they own that are labeled with Guppy, and close the issue.

# Technical Debt
## Guppy (CI): 
-  Each team closes Guppy debt issues

# CLEAN-UP EFFORT: Documentation 
## Pre-development

# Publications
## Pre-development