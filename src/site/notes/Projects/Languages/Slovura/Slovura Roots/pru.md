---
{"meaning":"bug, insect","origin":"(Czech) brouk","toki-pona":"pipi","dg-publish":true,"dg-path":"Slovura Roots/pru.md","permalink":"/slovura-roots/pru/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"bug, insect","origin":"(Czech) brouk","toki-pona":"pipi"}}
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

