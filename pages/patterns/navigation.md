---
layout: patterns
title: Navigation
permalink: /universal
description: The navigation pattern contains space for a logo, different page
  categories, and a search bar.
category: pattern
specification: >-
  

  * **On click** chosen page should be bolded to distinguish which page user is on 

  * **On click** the search icon leads user to search page where they can type search query
designimg: /assets/img/uploads/screen-shot-2022-01-19-at-11.10.26-am.png
schema:
  - fieldname: Navigation links
    type: navlink
    class: header-link
    required: true
    content: 25 characters maximum
    example: Collaborate
    notes: |-
      Font-family: PublicSans-Thin_Bold 
      Font-Weight: Thinbold 
      Font size: 18 px
---
