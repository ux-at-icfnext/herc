---
layout: patterns
title: Event Cards
permalink: /cards-with-media
parent: cards
category: pattern
specification: |-
  * **on hover** card flips displaying event information 
  * the full card is clickable
designimg: /assets/img/uploads/screen-shot-2022-01-19-at-2.05.32-pm.png
schema:
  - fieldname: Card Header
    type: H4
    class: "event_title "
    required: true
    content: 80 characters maxmimum
    example: "Health Equity: What is it and why it's important"
    notes: |
      Font-family: PTSans-Bold 
      Font-weight: Bold
  - fieldname: "Body "
    type: paragraph text
    class: event_body
    required: true
    content: 120 characters maximum
    notes: |
      Font-family: PublicSans-Thin_Regular 
      Font-weight: thinregular
---
Entire card is clickable and drop shadow appears when cards flips to description.