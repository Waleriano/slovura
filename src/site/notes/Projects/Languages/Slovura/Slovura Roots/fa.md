---
{"meaning":"fire, warmth, heat","origin":"(English) fire","toki-pona":"seli","dg-publish":true,"dg-path":"Slovura Roots/fa.md","permalink":"/slovura-roots/fa/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"fire, warmth, heat","origin":"(English) fire","toki-pona":"seli"}}
---


```base
formulas:
  Word: link(file.name, file.name.replace(/slovura_word_/, ""))
properties:
  note.meaning:
    displayName: Meaning
  note.logic:
    displayName: Logic
views:
  - type: table
    name: RootWords
    filters:
      and:
        - roots.Contains(this.file.name)
    order:
      - formula.Word
      - meaning
      - logic

```

