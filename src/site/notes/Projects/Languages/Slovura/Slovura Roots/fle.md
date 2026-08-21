---
{"meaning":"tool, device","origin":"(Czech) flexa","toki-pona":"ilo","dg-publish":true,"dg-path":"Slovura Roots/fle.md","permalink":"/slovura-roots/fle/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"tool, device","origin":"(Czech) flexa","toki-pona":"ilo"}}
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

