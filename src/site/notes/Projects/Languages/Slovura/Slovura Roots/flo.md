---
{"meaning":"money, wealth","origin":"(Czech) flok","toki-pona":"mani","dg-publish":true,"dg-path":"Slovura Roots/flo.md","permalink":"/slovura-roots/flo/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"money, wealth","origin":"(Czech) flok","toki-pona":"mani"}}
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

