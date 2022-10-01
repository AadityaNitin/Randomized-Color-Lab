name: 📄 Documentation issue
description: Found an issue in the documentation? You can use this one!
title: '[DOCS] <description>'
labels: ['documentation']
body:
  - type: textarea
    id: description
    attributes:
      label: Description
      description: Description of the question or issue, also include what you tried and what didn't work
    validations:
      required: true
  - type: textarea
    id: screenshots
    attributes:
      label: Screenshots
      description: Add screenshots if applicable
    validations:
      required: false