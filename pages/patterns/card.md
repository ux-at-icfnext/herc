---
layout: patterns
title: Card
permalink: /card
description: The default card style contains a simple title, body, and link to a
  destination page.
parent: cards
category: pattern
folder: card
specification: |
  - the full card is clickable
  - __onhover__ h3 shows hover color
  - __onclick/ontap__ h3 shows active color
schema:
  - fieldname: title
    type: h3
    class: card-title
    required: yes
    content: 80 characters max
    example: Cats are really cool dudes
    notes: title voice should be fun
  - fieldname: body
    type: text
    class: card-body
    required: yes
    content: 120 characters max
    example: Run off table persian cat jump eat fish hack. Paw at beetle and eat it
      before it gets away demand
    notes: "  "
  - fieldname: link text
    type: link text
    required: yes
    content: 40 characters max
    example: run little kitty
    notes: label text for link or button
    class: "  "
  - fieldname: url
    type: a href or button
    class: card-cta
    required: yes
    content: href link to destination page
    example: /card
    notes: "  "
csspath: patterns/{{ page.folder }}/{{ page.type }}.scss
htmlpath: patterns/{{ page.folder }}/{{ page.type }}.md
type: card
---

<!--- if extra information is needed for this pattern, write here in Markdown. -->
<!--- to learn markdown format go to https://docs.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax -->