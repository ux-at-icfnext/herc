---
layout: patterns
title: "Main Banner "
permalink: /homepage
description: The default main banner section of the homepage contains an image,
  header title, and body text.
parent: header-image
category: pattern
specification: ""
designimg: /assets/img/uploads/screen-shot-2022-01-19-at-9.48.05-am.png
schema:
  - fieldname: Title
    type: H1 bolded
    class: main-banner-title
    required: true
    content: |
      70 characters maximum
    notes: |-
      Font-family: PTSans-Bold 
      Font-weight: Bold 
      Text-align: Center 
      Blending: Normal
    example: "The Research Collaborative: Enhancing the way you learn"
  - fieldname: Sub-header
    type: H2 Regular
    class: main-banner-body
    content: 150 characters maximum
    example: We are always searching for new and better ways to understand the
      methods people use to find information
    notes: |-
      Font-family: PTSans-Regular
      Font-weight: Normal
      Text-align: Center 
      Blending: Normal 

      **This section is not required.
---
