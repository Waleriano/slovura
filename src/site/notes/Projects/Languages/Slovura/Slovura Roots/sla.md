---
{"meaning":"fun, playing, game, art","origin":"(Czech) slavit","toki-pona":"musi","dg-publish":true,"dg-path":"Slovura Roots/sla.md","permalink":"/slovura-roots/sla/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"fun, playing, game, art","origin":"(Czech) slavit","toki-pona":"musi"}}
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

