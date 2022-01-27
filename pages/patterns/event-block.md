---
layout: patterns
title: Event Block
permalink: /events
description: The default style contains a header, subheaders, and href link to
  an external source
parent: event-block
category: pattern
specification: "* **on click** link takes user to event information page."
designimg: /assets/img/uploads/screen-shot-2022-01-27-at-11.13.04-am.png
schema:
  - fieldname: Title
    required: true
    type: "H3 "
    class: event-title
    content: 10 character minimum
    example: "Spring Into Action: Fall Conference 2022"
  - fieldname: Subheading / Tag
    type: ""
    class: event-tag
    required: true
    content: Is either "virtual" or "in-person"
    example: Virtual
---
