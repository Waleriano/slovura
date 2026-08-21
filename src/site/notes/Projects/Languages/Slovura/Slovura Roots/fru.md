---
{"meaning":"fruit, vegetable","origin":"(English) fruit","toki-pona":"kili","dg-publish":true,"dg-path":"Slovura Roots/fru.md","permalink":"/slovura-roots/fru/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"fruit, vegetable","origin":"(English) fruit","toki-pona":"kili"}}
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

