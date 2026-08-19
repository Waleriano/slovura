---
{"meaning":"moon, night sky object","origin":"(Czech) luna, (English) clue","toki-pona":"mun","dg-publish":true,"dg-path":"Slovura Roots/klu.md","permalink":"/slovura-roots/klu/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"moon, night sky object","origin":"(Czech) luna, (English) clue","toki-pona":"mun"}}
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

