---
{"meaning":"enduring, wait, continue","origin":"(Spanish) esperar","toki-pona":"awen","dg-publish":true,"dg-path":"Slovura Roots/spe.md","permalink":"/slovura-roots/spe/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"enduring, wait, continue","origin":"(Spanish) esperar","toki-pona":"awen"}}
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

