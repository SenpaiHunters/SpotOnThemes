---
about: Suggest an idea for this project
assignees: ''
body:
  - attributes:
      value: |+
        ## Issue: Feature Request

        Request a new feature. If this doesn't look right, choose a different type.

    type: markdown
  - attributes:
      description: ✨ [Title here]
      label: Add a title
      placeholder: Feature title...
    type: input
    validations:
      required: true
  - attributes:
      description: Provide a clear and concise description of this feature request with any problems and solutions.
      label: Feature Request Description
      placeholder: Detailed description...
    type: textarea
    validations:
      required: true
  - attributes:
      description: Add screenshots to help explain this feature request, if applicable.
      label: Screenshots
      placeholder: Link to screenshots...
    type: textarea
    validations:
      required: false
  - attributes:
      description: Provide any additional information about this feature request.
      label: Additional Context
      placeholder: Any additional context...
    type: textarea
    validations:
      required: false
  - attributes:
      description: Please review your request before submitting.
      label: Final Checks
      options:
        - label: My issue title is descriptive
          required: true
        - label: This is a single feature request (multiple feature requests should be reported individually)
          required: true
    type: checkboxes
  - attributes:
      value: 🙏 Thank you for taking the time to report this feature request!
    type: markdown
description: Request a new feature. If this doesn't look right, choose a different type.
labels: ["feature"]
name: Feature Request
title: ✨ [Title here]
---