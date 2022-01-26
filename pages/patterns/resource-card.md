---
layout: patterns
title: Resource Card
permalink: /collaborate
description: "* **on hover** button text underlines"
parent: resource-card
category: pattern
specification: |-
  

  * Button should link use to external website
designimg: /assets/img/uploads/screen-shot-2022-01-26-at-4.20.41-pm.png
schema:
  - fieldname: Header
    type: H2
    class: resource-title
    required: true
    content: 50 characters max
    example: Fostering Connections with Robert Wood Johnson
  - fieldname: Button
    type: a href or button
    class: resource-button
    required: true
    content: the link moves user to external link
    notes: |-
      Padding: 15 px 
      Text-align: Center 
      Border Radius: 10 px
---
