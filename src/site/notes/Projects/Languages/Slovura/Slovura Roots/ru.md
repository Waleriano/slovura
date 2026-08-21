---
{"meaning":"hand, arm, five","origin":"(Czech) ruka","toki-pona":"luka","dg-publish":true,"dg-path":"Slovura Roots/ru.md","permalink":"/slovura-roots/ru/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"hand, arm, five","origin":"(Czech) ruka","toki-pona":"luka"}}
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

