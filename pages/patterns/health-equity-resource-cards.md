---
layout: patterns
title: "Health Equity Resource Cards "
permalink: /connect
description: The card will include header title and url link
parent: card
category: pattern
specification: |-
  * only the **url link** is clickable 
  * **on hover** url link becomes a darker hue
designimg: /assets/img/uploads/screen-shot-2022-01-19-at-1.48.00-pm.png
schema:
  - fieldname: Resource/Article Title
    type: H2 Bold
    required: true
    class: resource_header
    content: 60 characters maximum
    notes: |
      Font-family: Merriweather-Bold 
      Font-weight: Bold 
      Alignment: Center
  - fieldname: URL
    type: a href
    class: resource_link
    required: true
    content: link that takes user to resource page
---
