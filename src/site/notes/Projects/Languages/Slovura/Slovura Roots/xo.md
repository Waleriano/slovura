---
{"meaning":"what, which","origin":"(Czech) co","toki-pona":"seme","dg-publish":true,"dg-path":"Slovura Roots/xo.md","permalink":"/slovura-roots/xo/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"what, which","origin":"(Czech) co","toki-pona":"seme"}}
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

