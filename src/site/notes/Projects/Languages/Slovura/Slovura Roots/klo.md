---
{"meaning":"hunt, search","origin":"(Czech) klovat","toki-pona":"alasa","dg-publish":true,"dg-path":"Slovura Roots/klo.md","permalink":"/slovura-roots/klo/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"hunt, search","origin":"(Czech) klovat","toki-pona":"alasa"}}
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

