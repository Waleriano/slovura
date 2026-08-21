---
{"meaning":"feelings, emotion, heart","origin":"(English) feeling","toki-pona":"pilin","dg-publish":true,"dg-path":"Slovura Roots/fe.md","permalink":"/slovura-roots/fe/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"feelings, emotion, heart","origin":"(English) feeling","toki-pona":"pilin"}}
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

