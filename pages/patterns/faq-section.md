---
layout: patterns
title: FAQ Section
permalink: /collaborate
description: The default element will have a title space, 3-4 empty accordions,
  and space for an image
category: pattern
specification: |-
  * **on click (closed)** accordion opens displaying answer to question
  * **on click (opened)** accordion closes
designimg: /assets/img/uploads/screen-shot-2022-01-19-at-2.50.48-pm.png
schema:
  - fieldname: Title
    type: H1 Bold
    required: true
    class: FAQ_title
    content: 40 character maximimum
    example: Become a collaborator
    notes: |
      Font-family: Merriweather-Bold 
      Font-weight: Bold
  - fieldname: Question Section
    type: Accordion
    class: FAQ_body
    required: true
    content: |-
      Question: maximum of 70 characters 
      Answer: maximum of 250 characters
    example: >-
      Question: What is health equity?

      Answer: Health equity means that everyone has a fair and just opportunity to be healthier...
---
