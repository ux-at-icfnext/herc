---
layout: patterns
title: Social Media Block
permalink: /connect
description: This section contains the establishments logo, header, description,
  and social media links
parent: social
category: pattern
specification: "* Social Media Links are clickable"
designimg: /assets/img/uploads/screen-shot-2022-01-26-at-3.19.31-pm.png
schema:
  - fieldname: Header
    type: H2
    required: true
    class: social-header
    content: 25 characters max
    example: Health Equity Foundation
    notes: |
      Font-family: Merriweather-Bold 
      Text-align: Center 
  - fieldname: Body
    required: true
    class: social-body
    content: 150 characters maximum
    notes: "Content should be center aligned "
---
