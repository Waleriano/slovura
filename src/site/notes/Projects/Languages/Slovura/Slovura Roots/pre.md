---
{"meaning":"front, wall, chest, face","origin":"(Latin) pre-","toki-pona":"sinpin","dg-publish":true,"dg-path":"Slovura Roots/pre.md","permalink":"/slovura-roots/pre/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"front, wall, chest, face","origin":"(Latin) pre-","toki-pona":"sinpin"}}
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

