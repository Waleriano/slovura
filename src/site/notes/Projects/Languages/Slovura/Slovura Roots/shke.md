---
{"meaning":"strange, silly, drunk","origin":"(Czech) šašek","toki-pona":"nasa","dg-publish":true,"dg-path":"Slovura Roots/shke.md","permalink":"/slovura-roots/shke/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"strange, silly, drunk","origin":"(Czech) šašek","toki-pona":"nasa"}}
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

