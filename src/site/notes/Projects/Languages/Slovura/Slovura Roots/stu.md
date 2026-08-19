---
{"meaning":"surface, table, chair","origin":"(Czech) stůl","toki-pona":"supa","dg-publish":true,"dg-path":"Slovura Roots/stu.md","permalink":"/slovura-roots/stu/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"surface, table, chair","origin":"(Czech) stůl","toki-pona":"supa"}}
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

