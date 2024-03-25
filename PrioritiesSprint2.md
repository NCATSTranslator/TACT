These are the priorities for Sprint number 2, which runs from March 18, 2024 to April 15, 2024.
In this sprint, the Octopus build is in CI and the Lobster build is in Test.
Each priority has a list of subtasks that are to be completed within this sprint.

# Develop Pathfinder Query
## Pre-development work:
- Map out upcoming cycles culminating in release to production
- Initial UI planning and discussions
- Document the use of TRAPI for Pathfinder queries in the ReasonerAPI github repo.
- Provide input variables and data examples to the UI team
## Octopus (CI) work:
- ARAs implement prototype Pathfinder
- Evaluate performance and result quality

# MultiCURIE Query (MCQ)
## Pre-development work:
- Determine 2-3 specific use cases for the MultiCURIe Query: Set of Phenotypes to a Gene that have known inputs and expected outputs
- Finalize TRAPI structure for lookup and inferred MCQ, 
- Document MCQ TRAPI in the ReasonerAPI repo.
- Initial UI design
## Octopus (CI):
- Implement TRAPI 1.5 Beta

# Display Full KL/AT in the UI
## Pre-Development
- EPC provides helpdesk service to KPs implementing edge level annotations
- Discussion with UI around display of KL/AT annotations
## Octopus (CI):
- KPs annotate edges in their KGs with KL/AT terms
- ARAs annotate their created edges with KL/AT terms

# Treats Refactor
## Pre-Development
- DM and UI collaborate to ensure that the provenance of new inferred treats edges is correctly represented (design).
## Octopus (CI):
- ARAs implement new reasoning and scoring based on changes in treats edges from KPs
- Implement new CQS templates to regenerate former treats edges as predictions with aux graphs referring to the foundational edge.

# New Merged Scores
## Pre-Development
- Implement systematic analysis of results
- Update scoring document to include ARA scores
- Add DCG metrics to O&O benchmarks
## Octopus (CI):
- ARAs reduce ties to no more than 10 repeated scores in the top quartile of their results
- The confidence scoring reduces ties to no more than 10 repeated scores in the top quartile of its results (assuming no ties from ARAs)
- The ordering scoring reduces ties to no more than 10 repeated scores in the top quartile of its results (assuming no ties from confidence)
- UI deploys O&O merged score

# Scalability
## Octopus (CI):
- Sending Concurrent queries (MVP1&MVP2) in batch of 5,10,15,20,25,30 (CI Env)
## Lobster (Test):
- Sending Concurrent queries (MVP1&MVP2) in batch of 5,10,15,20,25,30 (TEST Env)

# CQS Workflows
## Pre-development
- Develop new MVP1 and MVP2 workflows
## Eel (DEV):
- develop mvp1-template4-service-provider-aeolus; push to CI at end of sprint
- develop mvp1-template5-spoke-chembl; push to CI at end of sprint
## Octopus (CI):
- finalize mvp1-template1-clinical-kps; push to TEST at end of sprint
- finalize mvp1-template3-openpredict; push to TEST at end of sprint
- Test the CI templates using the Testing Harness; TAQA

# Fix Failing Automated Tests
## Octopus (CI):
- Resolve Test-running Issues
- Each ARA should return no more than 75 failures
- Each ARA should have no more than 75 tests in which they do not return results
- CQS should return no more than 75 failures
- Implement all test runs from the Test Run Schedule that can currently be supported
- Implement MVP2 Tests
- Testing WG coordinates with ARAs and CQS to reach the above metrics

# Fix TAQA issues
## Octopus (CI):
- Determine 2 or 3 representatives who can review and close tickets
- Identify 5-10 issues that can be fully completed this cycle/sprint
- Triage TAQA issues into TACT priorities
- Work to close the identified issues

