---
{"meaning":"time, moment, period","origin":"(Czech) čas","toki-pona":"tenpo","dg-publish":true,"dg-path":"Slovura Roots/sha.md","permalink":"/slovura-roots/sha/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"time, moment, period","origin":"(Czech) čas","toki-pona":"tenpo"}}
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

