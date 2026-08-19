---
{"meaning":"way, manner, custom, road","origin":"(Czech) svoje","toki-pona":"nasin","dg-publish":true,"dg-path":"Slovura Roots/svo.md","permalink":"/slovura-roots/svo/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"way, manner, custom, road","origin":"(Czech) svoje","toki-pona":"nasin"}}
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

