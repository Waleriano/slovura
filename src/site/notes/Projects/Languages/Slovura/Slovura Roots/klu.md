---
{"meaning":"moon, night sky object","origin":"(Czech) luna, (English) clue","toki-pona":"mun","dg-publish":true,"dg-path":"Slovura Roots/klu.md","permalink":"/slovura-roots/klu/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"moon, night sky object","origin":"(Czech) luna, (English) clue","toki-pona":"mun"}}
---


```base
properties:
  file.name:
    displayName: Word
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
      - file.name
      - meaning
      - logic
    columnSize:
      file.name: 84

```

