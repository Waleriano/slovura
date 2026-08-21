---
{"meaning":"self","origin":"(Czech, Spanish) se","toki-pona":null,"dg-publish":true,"dg-path":"Slovura Roots/se.md","permalink":"/slovura-roots/se/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"self","origin":"(Czech, Spanish) se","toki-pona":null}}
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

