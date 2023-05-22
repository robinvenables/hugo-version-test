---
name: "Weekly Meeting Notes"
about: "Used for taking notes in our daily standups, with a new issue every week"
title: "Weekly Meeting Notes: {{ date | date('D') }} - {{ date | date('add', 5, 'days') | date('D MMM') }}"
labels:
  - "Meeting 💬"
---
### {{ date | date('dddd D MMM') }}
