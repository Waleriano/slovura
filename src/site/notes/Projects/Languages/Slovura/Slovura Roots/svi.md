---
{"meaning":"sweet, cute, sugar","origin":"(English) sweet","toki-pona":"suwi","dg-publish":true,"dg-path":"Slovura Roots/svi.md","permalink":"/slovura-roots/svi/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"sweet, cute, sugar","origin":"(English) sweet","toki-pona":"suwi"}}
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

