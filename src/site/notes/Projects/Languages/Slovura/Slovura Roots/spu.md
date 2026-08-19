---
{"meaning":"down, lowly","origin":"(Czech) spustit","toki-pona":"anpa","dg-publish":true,"dg-path":"Slovura Roots/spu.md","permalink":"/slovura-roots/spu/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"down, lowly","origin":"(Czech) spustit","toki-pona":"anpa"}}
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

