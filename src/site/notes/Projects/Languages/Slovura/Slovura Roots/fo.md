---
{"meaning":"make, activity, work, project","origin":"(Czech) foch, fortel","toki-pona":"pali","dg-publish":true,"dg-path":"Slovura Roots/fo.md","permalink":"/slovura-roots/fo/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"make, activity, work, project","origin":"(Czech) foch, fortel","toki-pona":"pali"}}
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

