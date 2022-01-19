---
layout: patterns
title: Subscription Panel
permalink: /connect
description: The panel contains a title, body copy, input fields, and a submission button
parent: submission_panel
category: pattern
specification: |-
  * Only the submit button is clickable 
  * the two input fields are required
designimg: /assets/img/uploads/screen-shot-2022-01-19-at-11.52.49-am.png
schema:
  - fieldname: Main header
    type: H2 Bold
    class: submission_panel_title
    required: true
    content: 30 characters maximum
    example: Join our mailing list
    notes: |
      Font-Family: Merriweather-Bold
      Font-weight: Bold 
      Alignment: Left
---
