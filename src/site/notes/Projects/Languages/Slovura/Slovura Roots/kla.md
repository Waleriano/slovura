---
{"meaning":"head, mind, control, lead","origin":"(Czech) hlava","toki-pona":"lawa","dg-publish":true,"dg-path":"Slovura Roots/kla.md","permalink":"/slovura-roots/kla/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"head, mind, control, lead","origin":"(Czech) hlava","toki-pona":"lawa"}}
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

