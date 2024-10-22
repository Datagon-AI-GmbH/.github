name: "Incident Management & Regression Testing"
about: "Log incidents that reached production and track fixes along with regression test creation."
title: "[Incident]: "
labels: ["bug", "incident", "regression-test"]
assignees: [""]

body:
  - type: markdown
    attributes:
      value: |
        ## Incident Summary
        - **Title**: [Brief, descriptive title]
        - **Date**: [MM/DD/YYYY]
        - **Reported By**: [Name]

  - type: textarea
    id: description
    attributes:
      label: Description
      description: "Provide a short description of the issue and its impact."
      placeholder: "Short description of the issue and its impact"
      value: ""

  - type: textarea
    id: affected_area
    attributes:
      label: Affected Area
      description: "Specify the module or feature impacted."
      placeholder: "Module/Feature impacted"
      value: ""

  - type: textarea
    id: steps_to_reproduce
    attributes:
      label: Steps to Reproduce
      description: "Provide the steps needed to reproduce the issue."
      placeholder: |
        1. Step 1
        2. Step 2
      value: ""

  - type: markdown
    attributes:
      value: |
        ## Subtasks

  - type: checkboxes
    id: subtasks
    attributes:
      label: Subtasks
      options:
        - label: "Fix the Incident"
          description: "Assigned developer works on fixing the issue."
        - label: "Create Regression Test"
          description: "Tester/developer creates the regression test for the issue."

  - type: textarea
    id: fix_status
    attributes:
      label: Fix the Incident - Details
      description: "Add details for fixing the issue, such as assignee, status, and PR link."
      placeholder: |
        - **Assigned To**: [Developer Name]
        - **Status**: [In Progress/Complete]
        - **PR Link**: [PR URL]

  - type: textarea
    id: regression_test_details
    attributes:
      l
