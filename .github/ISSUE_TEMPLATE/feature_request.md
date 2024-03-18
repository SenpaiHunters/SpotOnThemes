---
name: Feature Request
about: Suggest an idea for this project
title: "✨ [Title here]"
labels: ["feature"]
assignees: ""
description: Request a new feature.
body:
  - type: textarea
    attributes:
      label: Feature Request Description
      description: Provide a clear and concise description of this feature request with any problems and solutions.
    validations:
      required: true

  - type: textarea
    attributes:
      label: Screenshots
      description: Add screenshots to help explain this feature request, if applicable.
    validations:
      required: false

  - type: textarea
    attributes:
      label: Additional Context
      description: Provide any additional information about this feature request.
    validations:
      required: false

  - type: checkboxes
    attributes:
      label: Final Checks
      options:
        - label: My issue title is descriptive
          required: true
        - label: This is a single feature request (multiple feature requests should be reported individually)
          required: true

  - type: markdown
    attributes:
      value: Thank you for taking the time to report this feature request!
---
