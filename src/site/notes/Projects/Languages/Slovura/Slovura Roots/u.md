---
{"meaning":"or","origin":"(toki pona) anu","toki-pona":"anu","dg-publish":true,"dg-path":"Slovura Roots/u.md","permalink":"/slovura-roots/u/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"or","origin":"(toki pona) anu","toki-pona":"anu"}}
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

