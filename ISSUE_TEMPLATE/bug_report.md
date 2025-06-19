name: Bug Report
description: Report something that isn't working as expected.
labels: [bug]
body:
  - type: textarea
    id: what-happened
    attributes:
      label: What happened?
      placeholder: Describe the issue
    validations:
      required: true

  - type: textarea
    id: steps
    attributes:
      label: Steps to Reproduce
      placeholder: |
        1. Go to '...'
        2. Click on '...'
        3. See error
    validations:
      required: false

  - type: input
    id: version
    attributes:
      label: Version
      placeholder: e.g. v0.3.1

  - type: dropdown
    id: system
    attributes:
      label: Environment
      options:
        - Web (VaultNest UI)
        - Backend (VaultNest Engine)
        - Docker Container
        - Other
