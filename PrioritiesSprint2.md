These are the priorities for Sprint number 2, which runs from March 18, 2024 to April 15, 2024.
In this sprint, the Octopus build is in CI and the Lobster build is in Test.
Each priority has a list of subtasks that are to be completed within this sprint.

# Develop Pathfinder Query
## Pre-development work:
- Map out upcoming cycles culminating in release to production
- Initial UI planning and discussions
## Octopus (CI) work:
- ARAs implement prototype Pathfinder
- Evaluate performance and result quality

# MultiCURIE Query (MCQ)
## Pre-development work:
- Determine 2-3 specific use cases for the MultiCURIe Query: Set of Phenotypes to a Gene that have known inputs and expected outputs
- Finalize TRAPI structure for lookup and inferred MCQ
- Initial UI design
## Octopus (CI):
- Implement TRAPI 1.5 Beta

# Display Full KL/AT in the UI
## Pre-Development
- EPC provides helpdesk service to KPs implementing edge level annotations
- Discussion with UI around display of KL/AT annotations
## Octopus (CI):
- KPs annotate edges in their KGs with KL/AT terms
- Test that the UI correctly represents the foundational edge

# Treats Refactor
## Octopus (CI):
- ARAs implement new reasoning and scoring based on changes in treats edges from KPs
- Implement new CQS templates to regenerate former treats edges as predictions with aux graphs referring to the foundational edge.

# New Merged Scores
## Pre-Development

# Scalability
## Octopus (CI):
- Sending Concurrent queries (MVP1&MVP2) in batch of 5,10,15,20,25,30 (CI Env)
## Lobster (Test):
- Sending Concurrent queries (MVP1&MVP2) in batch of 5,10,15,20,25,30 (TEST Env)

# CQS Workflows
## Pre-development
- Develop MVP2 workflows
## Eel (DEV):
- Develop new treats workflows
## Octopus (CI):
- Test Paths A, E

# Fix Failing Automated Tests
## Octopus (CI):
- Resolve Test-running Issues
- All ARAs should return no more than 75 failures
- All ARAs should have no more than 75 tests in which they do not return results
- CQS should return no more than 75 failures
- Implement all test runs from the Test Run Schedule that can currently be supported

# Fix TAQA issues
## Octopus (CI):
- Determine 2 or 3 representatives who can review and close tickets
- Identify 5-10 issues that can be fully completed this cycle/sprint
- Work to close the identified issues

