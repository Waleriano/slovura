---
{"meaning":"have, hold, own","origin":"(Czech) mít","toki-pona":"jo","dg-publish":true,"dg-path":"Slovura Roots/me.md","permalink":"/slovura-roots/me/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"have, hold, own","origin":"(Czech) mít","toki-pona":"jo"}}
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

