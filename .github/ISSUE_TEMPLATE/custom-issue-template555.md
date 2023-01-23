---
name: Custom issue template555
about: Describe this issue template's purpose here.
title: ''
labels: ''
assignees: ''

---

- type: dropdown
  id: download
  attributes:
    label: How did you download the software?
    options:
      - Homebrew
      - MacPorts
      - apt-get
      - Built from source
  validations:
    required: true
