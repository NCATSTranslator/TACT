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
## Guppy (CI) work:
- ARAs Pass TRAPI validation
- Non-responding ARAs return 501
- ARS to test merging of Pathfinder responses
- ARAs implement Constraints

# MultiCURIE Query (MCQ)
## Guppy (CI) work:
- Genetics KP to deploy GeneSet Enrichment
- Complete inferred mode MCQ in ARA
- Non responding ARAs return 501
- Test results on example queries
- ARS to test merging of MCQ responses
- UI inspects inferred results; begins development

# LLM Summarization 
## Pre-development work:
- Assess effectiveness and usefulness of each proposed approach.  Engineering and cost assessment for each approach.  Assess cost, quality, and other tradeoffs for different "open" and non-open LLMs, and determine if a model-agnostic approach is feasible.

# O&O Based grouping in the UI 
## Guppy (CI):
## Fugu (TEST):

# Display Full KL/AT in the UI
## Guppy (CI):
- KPs complete implementation; reduce level of "unknown/not provided"
- Complete QA of KP implementation
## Fugu (TEST):
- Initial UI implmentation; dependent on KP completion

# Treats Refactor
## Guppy (CI):
- Clinical Trial KP deploys TRAPI endpoint; SmartAPI registration
- KPs (SPOKE, KG2, MolePro, SP) to start removing Chembl Clinical Trial ingests

Move to Sprint 6:
- KP remove Chembl Clinical Trials ingests

# Develop Automated Tests
## Pre-Development
- Develop Benchmarking Suite
- Develop MCQ Suite
- Develop Pathfinder Suite
- Work on TRAPI Validation Runner
- Address issues in the Test repo to improve the test cases
- Programmatically address test case names and identifiers
- Update Evaluation of Top Answer to move towards an absolute cutoff of 30

# Fix Failing Automated Tests
## Guppy (CI):
- Each ARA is expected to pass 55 tests from the Top Answer Sprint 5 test suite
- Each ARA is expected to pass 360 tests from the Never Show Sprint 5 test suite

# Collect Feedback Issues
## Fugu (TEST):
- Each team must perform manual testing of the Fugu release in TEST and report issues to the Feedback repo
between August 2 and August 9, 2024
- TAQA will review and prioritize the discovered issues

# Fix Feedback issues
## Guppy (CI):
- Each team will fix issues they own that are labeled with Guppy, and close the issue.

# Technical Debt
## Guppy (CI): 
-  Each team closes Guppy debt issues

# CLEAN-UP EFFORT: Documentation 
## Pre-development
- Each team closes Guppy documentation issues

# Publications
## Pre-development
- Collect feedback and use cases
