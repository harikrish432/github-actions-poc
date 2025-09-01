---
name: Feature request
about: Suggest an idea for this project
title: ''
labels: ''
assignees: ''

---

- type: dropdown
      id: assignee
      attributes:
        label: Assignee
        multiple: false # Set to true for multi-select dropdown
        options:
          - option: "John Doe"
          - option: "Jane Smith"
          - option: "Unassigned"
      validations:
        required: true
