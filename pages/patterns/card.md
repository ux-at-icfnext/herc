---
layout: patterns
permalink: "/card"
title: "Card"
description: "The default card style contains a simple title, body and link to a destination page"
parent: "cards"
category: pattern
folder: card
path: "partials"
type: card
greetings: Greetings {{ page.first_name }} {{ page.last_name }}!

schema:
    - fieldname: title
      type: h3
      class: card-title
      required: yes
      content: 80 characters max
      example: "Cats are really cool dudes"
      notes: "title voice should be fun"
    - fieldname: body
      type: text
      class: card-body
      required: yes
      content: 120 characters max
      example: "Run off table persian cat jump eat fish hack. Paw at beetle and eat it before it gets away demand"
    - fieldname: link text
      type: link text
      required: yes
      content: 40 characters max
      example: "run little kitty"
      notes: "label text for link or button"
    - fieldname: url
      type: a href or button
      class: card-cta
      required: yes
      content: href link to destination page
      example: "/card"
---
