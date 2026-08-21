---
{"meaning":"more, after","origin":"(Bulgarian) po","toki-pona":null,"dg-publish":true,"dg-path":"Slovura Roots/po.md","permalink":"/slovura-roots/po/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"more, after","origin":"(Bulgarian) po","toki-pona":null}}
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

