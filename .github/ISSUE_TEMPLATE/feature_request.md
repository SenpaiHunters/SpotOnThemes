---
name: Feature Request
about: Suggest an idea for this project
title: "✨ [Title here]"
labels: ["feature"]
assignees: ""

description: "Request a new feature. If this doesn't look right, choose a different type."
body:
  - type: markdown
    attributes:
      value: "## Issue: Feature Request\n\nRequest a new feature. If this doesn't look right, choose a different type.\n\n"

  - type: input
    attributes:
      label: Add a title
      description: "✨ [Title here]"
      placeholder: "Feature title..."
    validations:
      required: true

  - type: textarea
    attributes:
      label: Feature Request Description
      description: "Provide a clear and concise description of this feature request with any problems and solutions."
      placeholder: "Detailed description..."
    validations:
      required: true

  - type: textarea
    attributes:
      label: Screenshots
      description: "Add screenshots to help explain this feature request, if applicable."
      placeholder: "Link to screenshots..."
    validations:
      required: false

  - type: textarea
    attributes:
      label: Additional Context
      description: "Provide any additional information about this feature request."
      placeholder: "Any additional context..."
    validations:
      required: false

  - type: checkboxes
    attributes:
      label: Final Checks
      description: "Please review your request before submitting."
      options:
        - label: "My issue title is descriptive"
          required: true
        - label: "This is a single feature request (multiple feature requests should be reported individually)"
          required: true

  - type: markdown
    attributes:
      value: "🙏 Thank you for taking the time to report this feature request!"

---