---
{"meaning":"white, light-colored","origin":"(Czech) světlý","toki-pona":"walo","dg-publish":true,"dg-path":"Slovura Roots/sve.md","permalink":"/slovura-roots/sve/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"white, light-colored","origin":"(Czech) světlý","toki-pona":"walo"}}
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

