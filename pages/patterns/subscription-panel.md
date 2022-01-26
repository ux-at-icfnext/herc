---
layout: patterns
title: Subscription Panel
permalink: /connect
description: The panel contains a title, body copy, input fields, and a submission button
parent: submission_panel
category: pattern
specification: |-
  * Only the **submit button** is clickable 
  * the **two input fields** are required
designimg: /assets/img/uploads/screen-shot-2022-01-26-at-3.55.21-pm.png
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
  - fieldname: Body copy
    type: "Paragraph "
    class: subscription_panel_body
    notes: |-
      Font-family: PublicSas-Thin_Regular 
      Font-size: 20 px 
      Font-weight: thinregular 
      **This section is not required
    content: 200 characters maximum
    example: By joining our list serv, you will gain access to our latest...
  - fieldname: Input Field Email
    type: "Paragraph Text "
    class: input_field_email
    required: true
    content: "Email needs to have an ampersat. "
    example: collaborative@gmail.com
  - fieldname: Terms and Conditions Copy
    type: "Paragraph text, italicized "
    class: subscription_panel_terms
    content: 300 characters maximum
    example: ""
    notes: |-
      Font-family: PublicSans-ThinkItalic_Italic
      Fonty Style: Italic 
  - fieldname: Submit Button
    type: Rectangle
    class: subscription_panel_button
    content: 40 character maximum
    example: Subscribe to list serv
    notes: |
      Font-Family: PublicSans-Thin_Bold 
      Font-weight: Thinbold
---
