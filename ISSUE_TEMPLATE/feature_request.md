name: Feature Request
description: Suggest an idea for a new feature
labels: [enhancement]
body:
  - type: textarea
    id: idea
    attributes:
      label: Feature description
      placeholder: What's the feature and how would it help?
    validations:
      required: true

  - type: textarea
    id: why
    attributes:
      label: Why is this useful?
      placeholder: What problem does it solve or improve?
