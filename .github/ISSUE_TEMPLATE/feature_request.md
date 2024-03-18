---
name: Feature Request
about: Suggest an idea for this project
title: "✨ [Title here]"
labels: ["feature"]
assignees: ""

description: Request a new feature to enhance the project.
body:
  - type: textarea
    attributes:
      label: Feature Request Description
      description: "Provide a clear and concise description of the feature you're proposing. Include any problems it aims to solve and how it could be implemented."
    validations:
      required: true

  - type: textarea
    attributes:
      label: Potential Alternatives
      description: "Describe any alternative solutions or features you've considered. This helps us understand your thought process and explore different angles."
    validations:
      required: false

  - type: textarea
    attributes:
      label: Screenshots or Mockups
      description: "If possible, add screenshots or mockups to help visualize the feature request."
    validations:
      required: false

  - type: textarea
    attributes:
      label: Additional Context
      description: "Provide any other context or information that could help us understand this feature request better."
    validations:
      required: false

  - type: checkboxes
    attributes:
      label: Final Checks
      description: "Please review your request before submitting."
      options:
        - label: "I have provided a descriptive title for my feature request."
          required: true
        - label: "This is a single feature request (for multiple features, please submit them individually)."
          required: true

  - type: markdown
    attributes:
      value: "Thank you for taking the time to submit this feature request! We appreciate your effort to improve the project."

---