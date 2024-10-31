This document is PROVISIONAL and will be udpated at the beginning of sprint 6 and subject to a new vote.

These are the priorities for Sprint number 6, which runs from October 11, 2024 to November 30, 2024. 

In this sprint, the builds are in these environments: 

- PROD: Guppy
- TEST: Hammerhead 
- CI: Ichthyosaur
- DEV: Jellyfish

Each priority has a list of subtasks that are to be completed within this sprint.

Note that ARAs will be required to implement at least one of MCQ, Pathfinder, or LLM.

# Develop Pathfinder Query
# Pre-dev:
- Develop new TRAPI encoding

# Develop Set Input
## Pre-dev
- Revisit TRAPI structure
- Make TRAPI proposal for meta KG
## Ichthyosaur (CI):
- Implement arbitrary 1-hops
## Hammerhead (TEST) work:
- Flesh out UI ideas

# LLM Summarization 
## Ichthyosaur (CI):
- Implement a prototype UI incorporating Karthik's LLM summarization
- Karthik investigate switching from OpenAI to Open Source
- Kaiwen produces demo over a subset of papers and questions

# O&O Based grouping in the UI 
## Pre-dev
- Investigate ARA cross-scoring. 
- Try to run a cross-scoring experiment based on Test Assets.
## Ichthyosaur (CI):
- Improve performance of novelty scoring

# Display Full KL/AT in the UI
## Hammerhead (TEST):
- Final UI implementation

# Develop Automated Tests
## Pre-Dev
- Decide on any extra information to collect via open telemetry (OTEL)
## Ichthyosaur (CI):
- Audit OTEL implementations
- Implement benchmark testing

# Fix Failing Automated Tests
## Ichthyosaur (CI):
- ARAs are expected to pass 60 TopAnswer tests
- ARAs are expected to pass 400 NeverShow tests

# Collect Feedback Issues
## Hammerhead (TEST):
- Each team must perform manual testing of the Guppy release in TEST and report issues to the Feedback repo
between October 13 and October 20, 2024
- TAQA will review and prioritize the discovered issues

# Fix Feedback issues
## Ichthyosaur (CI):
- Each team will fix issues they own that are labeled with Fugu, Guppy, or Hammerhead, and close the issue.

# Technical Debt
## Ichthyosaur (CI): 
-  Each team closes Hammerhead (or previous) debt issues

# CLEAN-UP EFFORT: Documentation 
## Pre-development

# Publications
## Development
- Publication complete
