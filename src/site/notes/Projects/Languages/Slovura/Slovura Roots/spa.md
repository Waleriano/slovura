---
{"meaning":"sleep, rest","origin":"(Czech) spát","toki-pona":"lape","dg-publish":true,"dg-path":"Slovura Roots/spa.md","permalink":"/slovura-roots/spa/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"sleep, rest","origin":"(Czech) spát","toki-pona":"lape"}}
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

