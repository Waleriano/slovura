---
{"meaning":"old, ancient","origin":"(Czech) pra-","toki-pona":"majuna","dg-publish":true,"dg-path":"Slovura Roots/pra.md","permalink":"/slovura-roots/pra/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"old, ancient","origin":"(Czech) pra-","toki-pona":"majuna"}}
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

