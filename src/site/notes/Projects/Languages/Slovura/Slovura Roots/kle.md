---
{"meaning":"grain, cereal, bread, pasta","origin":"(Czech) chleba","toki-pona":"pan","dg-publish":true,"dg-path":"Slovura Roots/kle.md","permalink":"/slovura-roots/kle/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"grain, cereal, bread, pasta","origin":"(Czech) chleba","toki-pona":"pan"}}
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

