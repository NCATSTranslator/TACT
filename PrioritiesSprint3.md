These are the priorities for Sprint number 3, which runs from April 29, 2024 to May 26, 2024. 
In this sprint, the Eel build is in CI and the Octopus build is in Test. Each priority has a list of subtasks that are to be completed within this sprint.

Each priority has a list of subtasks that are to be completed within this sprint.

# Develop Pathfinder Query
## Pre-development work:
- ?
## Octopus (CI) work:
- Probably design new landing page to distinguish types of interactions (templated query, pathfinder, multiquery(?))
- Design query selection interface - Dependencies: decisions on categories of nodes to be allowed as starting points and any other factors allowed for query selection 
- User testing path grouping strategies
- Design results page path (conceptually)(not implemented)  and graph display (similar to results now) - Dependencies: understanding of the number of paths and how they will be grouped
- Research to identify new facets needed. e.g. facets for other categories - Dependencies: pathfinder data examples
- User research filter designs for new filters like metaedge type or other. 
- Evaluate performance and result quality from prototype implementations
- Provides example datasets to UI

# MultiCURIE Query (MCQ)
## Pre-development work:
- ?
## Octopus (TEST):
- TRAPI 1.5 finalized and released 
- Designs multi curie selection -  requires interface to add and subtract select curies (how many max?)
- Investigate additional facets needed ( e.g. curie match facet, other specific to starting or ending node category if neccesary)
- User research filter designs for new filters like metaedge type or other.
## Eel (CI):
- Relevant KPs implement lookup MCQ

# Display Full KL/AT in the UI
## Pre-Development
-?
## Octopus (TEST):
- Last few KPs/ARAs annotate edges with KL/AT terms (See status table here)
- UI team implements full KL/AT tags in UI display (define paradigm to accommodate this info, which may include user friendly synonyms, new icons/badges, updated EPC modal tables, etc).
- Determine how to display KL/AT for KPs/ARAs that have not yet implemented edge-level annotations (may fall back to infores-based annotation?)
- ARAs/O&O plans for utilizing KL/AT information in their scoring approaches
- Define next EPC area to standardize and implement in data and UI.

# Treats Refactor
## Pre-Development
-?
## Octopus (TEST):
- UI implements "treats" refactor including provenance

# Scalability
## Eel (CI):
- Sending Concurrent queries (MVP1&MVP2) in batch of 5,10,15,20,25,30 (Test Env)

# CQS Workflows
## Pre-development
- Develop new CQS MVP1, MVP2, and MVPXX templates
## Eel (CI):
- Push mvp1-template5-spoke-chembl to DEV
## Octopus (TEST):
-  Push mvp1-template1-clinical-kps, mvp1-template3-openpredict, and mvp1-template4-bte-aeolus to TEST

# Fix Failing Automated Tests
## Eel (CI):
- Deploy validation test runner
- Deploy stress test runner
- Implement MVP2 benchmarks

# Fix TAQA issues
## Eel (CI):
- Identify 5-10 issues that can be fully completed this cycle/sprint
