These are the priorities for Sprint number 3, which runs from April 29, 2024 to May 26, 2024. 
In this sprint, the Eel build is in CI and the Octopus build is in Test. Each priority has a list of subtasks that are to be completed within this sprint.

Each priority has a list of subtasks that are to be completed within this sprint.  

Note that ARAs will be required to implement either MCQ or Pathfinder (or both).

# Develop Pathfinder Query
## Pre-development work:
- Design new landing page to distinguish types of interactions (templated query, pathfinder, multiquery(?)) (UI)
- Design query selection interface - Dependencies: decisions on categories of nodes to be allowed as starting points and any other factors allowed for query selection (UI, ARAs)
- User testing path grouping strategies (UI, ARAs)
- Design results page path  and graph display (similar to results now) - Dependencies: understanding of the number of paths and how they will be grouped (UI, ARAs)
- Research to identify new facets needed. e.g. facets for other categories - Dependencies: pathfinder data examples (UI, ARAs)
- User research filter designs for new filters like metaedge type or other. (UI)
- Provides example datasets to UI (ARAs)
## Octopus (CI) work:
- Evaluate performance and result quality from prototype implementations (ARAs)

# MultiCURIE Query (MCQ)
## Pre-development work:
- Designs multi curie selection -  requires interface to add and subtract select curies (how many max?) (UI)
- Investigate additional facets needed ( e.g. curie match facet, other specific to starting or ending node category if neccesary) (UI)
- User research filter designs for new filters like metaedge type or other. (UI)
- ## Eel (CI):
- Relevant KPs implement lookup MCQ (KPs)
- NodeNorm implements set ID method
## Octopus (TEST):
- TRAPI 1.5 finalized and released (ARAs, KPs, UI)

# Display Full KL/AT in the UI
## Pre-Development
- ARAs/O&O plans for utilizing KL/AT information in their scoring approaches (ARA, O&O)
- Define next EPC area to standardize and implement in data and UI. (EPC)
- ## Eel (CI):
- Last few KPs/ARAs annotate edges with KL/AT terms (See status table [here](https://docs.google.com/document/d/16agzJB0OlR8z-zU3nTivYYIo09sdayN-tu8lbrZyTXY/edit?pli=1#bookmark=id.kz0zera1i398)) (KPs, ARAs)
## Octopus (TEST):
- UI team implements full KL/AT tags in UI display (define paradigm to accommodate this info, which may include user friendly synonyms, new icons/badges, updated EPC modal tables, etc). (UI)
- Determine how to display KL/AT for KPs/ARAs that have not yet implemented edge-level annotations (may fall back to infores-based annotation?) (UI)

# Treats Refactor
## Octopus (TEST):
- UI implements "treats" refactor including provenance (UI)

# Scalability
## Eel (CI):
- Sending Concurrent queries (MVP1&MVP2) in batch of 5,10,15,20,25,30 (Test Env)

# CQS Workflows
## Eel (CI):
-  Test and iterate mvp1-template1-clinical-kps, mvp1-template3-openpredict, and mvp1-template4-bte-aeolus
-  Push mvp1-template1-clinical-kps, mvp1-template3-openpredict, and mvp1-template4-bte-aeolus to TEST

# Fix Failing Automated Tests
The current number of tests is 484, so the number of new tests is (Number of tests - 484)
## Pre-Development
- Implement MVP2 benchmarks (Testing)
## Eel (CI):
- Deploy validation test runner (Testing)
- Deploy stress test runner (Testing)
- Reduce Test Failures for ARAs to < (100 + Number of New Tests) (ARAs)
- Reduce No-Results for ARAs to < (50 + Number of New Tests) (ARAs)
- Reduce Test Failures for CQS to < (20 + Number of New Tests) (CQS)

# Fix TAQA issues
## Eel (CI):
- Identify 5-10 issues that can be fully completed this cycle/sprint
