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
  - fieldname: Body copy
    type: "Paragraph "
    class: subscription_panel_body
    notes: |-
      Font-family: PublicSas-Thin_Regular 
      Font-size: 20 px 
      Font-weight: thinregular 
      **This section is not required
    content: 200 characters maxmium
    example: By joining our list serv, you will gain access to our latest...
  - fieldname: Input Field Name
    type: Paragraph text
    class: input_field_name
    required: true
    content: 4 character minimum
    example: Harold Shaw
  - fieldname: Input Field Email
    type: "Paragraph Text "
    class: input_field_email
    required: true
    content: "Email needs to have an ampersat. "
    example: collaborative@gmail.com
---
