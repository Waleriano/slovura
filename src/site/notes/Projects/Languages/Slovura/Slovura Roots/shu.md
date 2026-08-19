---
{"meaning":"sex, sexual","origin":"(Czech) šukat","toki-pona":"unpa","dg-publish":true,"dg-path":"Slovura Roots/shu.md","permalink":"/slovura-roots/shu/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"sex, sexual","origin":"(Czech) šukat","toki-pona":"unpa"}}
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

