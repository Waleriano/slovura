---
{"meaning":"market, trade","origin":"(Czech) sleva","toki-pona":"esun","dg-publish":true,"dg-path":"Slovura Roots/sle.md","permalink":"/slovura-roots/sle/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"market, trade","origin":"(Czech) sleva","toki-pona":"esun"}}
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

