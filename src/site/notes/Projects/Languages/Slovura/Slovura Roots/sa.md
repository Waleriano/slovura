---
{"meaning":"same, similar, equal, like","origin":"(English) same","toki-pona":"sama","dg-publish":true,"dg-path":"Slovura Roots/sa.md","permalink":"/slovura-roots/sa/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"same, similar, equal, like","origin":"(English) same","toki-pona":"sama"}}
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

