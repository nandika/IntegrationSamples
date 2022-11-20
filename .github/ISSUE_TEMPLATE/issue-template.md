---
name: Issue Template
about: 'Standardize the Issue creation so that all necessary information is capture
  at the time of issue creation '
title: "[Bug Report]"
labels: '[bug, triage]'
assignees: ''
  - octocat 

body : 
  - type: markdown 
    attributes : 
      value: | 
        Thanks for taking time to fill out this bug report !
  - type: input
    id: contact
    attributes: 
      label: Contact Details 
      description: How can we get in touch with you if we need more info
      placeholder: ex. email@example.com
    validations:
      required: false 
  - type: textarea
    id: what happened 
    attributes:
      description: Also tel us what did you expect to happen 
      placeholder: Tell us what you see
      value: "A bug happened"
    validations: 
      required: true 
      

---

