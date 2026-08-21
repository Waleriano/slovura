---
{"meaning":"eat, consume, food","origin":"(toki pona) moku","toki-pona":"moku","dg-publish":true,"dg-path":"Slovura Roots/mo.md","permalink":"/slovura-roots/mo/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"eat, consume, food","origin":"(toki pona) moku","toki-pona":"moku"}}
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

