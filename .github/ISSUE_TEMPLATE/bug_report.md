---
name: Bug report
about: Create a report to help us improve
title: ''
labels: ''
assignees: ''

---

body:
- type: input
  id: prevalence
  attributes:
    label: Bug prevalence
    description: "How often do you or others encounter this bug?"
    placeholder: "Example: Whenever I visit the personal account page (1-2 times a week)"
  validations:
    required: true
