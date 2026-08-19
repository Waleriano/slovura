---
{"meaning":"mouth, lips, jaw, oral","origin":"(Czech) pusa","toki-pona":"uta","dg-publish":true,"dg-path":"Slovura Roots/pu.md","permalink":"/slovura-roots/pu/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"mouth, lips, jaw, oral","origin":"(Czech) pusa","toki-pona":"uta"}}
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

