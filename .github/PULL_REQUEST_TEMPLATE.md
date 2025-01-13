name: "Pull Request"
description: "Template for pull requests"
title: "[PR]: "
labels: [needs-triage]
body:
  - type: textarea
    attributes:
      label: "Description"
      placeholder: "Describe the changes in this pull request"
      description: |
        Provide a detailed description of the changes in this pull request, including the purpose and any relevant context.
    validations:
      required: true

  - type: textarea
    attributes:
      label: "Related Issues"
      placeholder: "List any related issues"
      description: |
        List any related issues that this pull request addresses. For example:
        - Fixes #123
        - Closes #456
    validations:
      required: false

  - type: textarea
    attributes:
      label: "Checklist"
      description: |
        Provide a checklist of tasks completed in this pull request. For example:
        - [ ] Task 1: Implemented feature A
        - [ ] Task 2: Added tests for feature A
        - [ ] Task 3: Updated documentation
      placeholder: "List the tasks completed in this pull request"
    validations:
      required: true
