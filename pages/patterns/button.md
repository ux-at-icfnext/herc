---
layout: patterns
title: Button
permalink: /button
description: The button style contains padding around all 4 sides with left and
  right padding allowing text to stay center aligned.
category: pattern
specification: |-
  

  * **on hover** button changes to darker hue
designimg: /assets/img/uploads/screen-shot-2022-01-19-at-10.36.49-am.png
schema:
  - fieldname: Button Text
    type: "H3 "
    required: true
    content: 40 characters maximum
    example: View upcoming events
    notes: |-
      Font-family: PublicSans-Thin_Bold 
      Font-weight: Thinbold
      Text-align: Center
  - fieldname: Button Container
    required: true
    notes: |-
      Height: 82 px 
      Width: 560 px 
      Boder-Radius: 10 px
      Blending: Normal
    type: Rectangle
    class: button-container
---
