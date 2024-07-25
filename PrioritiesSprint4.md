These are the priorities for Sprint number 4, which runs from June 17, 2024 to July 19, 2024. 

In this sprint, the builds are in these environments: 

- PROD: Octopus
- TEST: Eel 
- CI: Fugu
- DEV: Guppy

Each priority has a list of subtasks that are to be completed within this sprint.

Note that ARAs will be required to implement at least one of MCQ, Pathfinder, or LLM.

# Develop Pathfinder Query
## Pre-development work:
- Develop automated tests
## Fugu (CI) work:
- Implement Constraints
- Improve Results
- Evaluate walltime performance and set goals

# MultiCURIE Query (MCQ)
## Pre-development work:
- Develop automated tests
- Develop Drug Side Effect Use Case
## Fugu (CI):
- ARA Implementation of Creative Mode
- Improve KP results for Phenotypes to Disease
- Implement Set IDs in NodeNorm

# LLM Summarization 
## Pre-development work:
- Experiment with and refine the summarization idea: Decide whether we will implement single-answer summarization, all-answers summarization, user querying over answers (RAG-like), or other approaches.

# O&O Based grouping in the UI 
## Pre-development work:
- User testing to determine effectiveness of chemical grouping based on ATC and Chebi roles
- User testing to determine effectiveness of gene grouping based on Genetics KP Gene Sets and PFOCR
## Fugu (CI):
- Implementation of Gene Set grouping API (Genetics KP)

# Display Full KL/AT in the UI
## Pre-Development
- Begin QA of KP implementation
## Fugu (CI):
- Remaining KPs implement KL/AT

# Develop Automated Tests
## Pre-Development
- Add MVP2 tests to Benchmarking Suite
- Implement automated tests for MCQ
- Revise test cases based on ARA feedback

# Fix Failing Automated Tests
## Fugu (CI):
- Each ARA is expected to pass 40 tests from the Sprint 4 test suite, which focuses on TopAnswer results.

# Collect Feedback Issues
## Eel (TEST):
- Each team must perform manual testing of the Eel release in TEST and report issues to the Feedback repo
between June 26 and July 3, 2024
- TAQA will review and prioritize the discovered issues

# Fix Feedback issues
## Pre-development
- Each team will review Feedback issues that they are responsible for and label them with either Eel, Fugu, Guppy, Hammerhead, or Phase 3, indicating the release in which a fix is expected.
## Fugu (CI):
- Each team will fix issues they own that are labeled with Fugu, and close the issue.
## Eel (TEST):
- Each team will fix issues labled with Eel, and close the issue.  Eel fixes are reserved for high-priority show stoppers.

# Technical Debt
## Pre-development
- Each team will assess technical debt items and create issues in their project repos tagged with "debt" 
- Each team will link each debt issue to a grouping issue in the Feedback repo based on the expected release in which the issue will be closed. (Fugu, Guppy, or Hammerhead)
## Fugu (CI): 
-  Each team closes Fugu debt issues

# CLEAN-UP EFFORT: Documentation 
## Pre-development
- Assess all documentation including (wiki pages, GH readme, GH pages, TRAPI docs, etc) and decide what requires effort in upcoming sprints.
- For infores/wiki: 
  1. get new UI MVP1/MVP2 dump from Andy; 
  2. reconcile new dump with previous G-sheet and Infores Catalog; 
  3. identify gaps in those primary knowledge sources that are being exposed via the UI in Octopus PROD release; 
  4. highlight ARA wiki pages for review

# Publications
## Pre-development
- Identify target journal
- Form core writing team
- Define scope of MS