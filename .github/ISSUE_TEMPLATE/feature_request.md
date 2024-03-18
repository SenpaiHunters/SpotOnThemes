---
name: Feature Request
description: Suggest an idea for this project
title: "[Title here]"
labels: ["feature"]
assignees: ""
body:
  - type: markdown
    attributes:
      value: "## Issue: Feature Request\n**Request a new feature.** If this doesn't look right, choose a different type."
  - type: input
    id: title
    attributes:
      label: "Add a title"
      description: "Provide a clear and concise title for your feature request."
      placeholder: "[Title here]"
    validations:
      required: true
  - type: textarea
    id: feature-request-description
    attributes:
      label: "Feature Request Description"
      description: "Provide a clear and concise description of this feature request with any problems and solutions."
      placeholder: "Describe the feature request here..."
    validations:
      required: true
  - type: textarea
    id: screenshots
    attributes:
      label: "Screenshots"
      description: "Add screenshots to help explain this feature request, if applicable."
      placeholder: "You can add links to screenshots here..."
    validations:
      required: false
  - type: textarea
    id: additional-context
    attributes:
      label: "Additional Context"
      description: "Provide any additional information about this feature request."
      placeholder: "Any additional context..."
    validations:
      required: false
  - type: checkboxes
    id: final-checks
    attributes:
      label: "Final Checks"
      description: "Please confirm the following:"
      options:
        - label: "My issue title is descriptive."
          required: true
        - label: "This is a single feature request (multiple feature requests should be reported individually)."
          required: true
---