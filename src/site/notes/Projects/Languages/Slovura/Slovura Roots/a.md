---
{"meaning":"emphasis, confirmation","origin":"(toki pona) a","toki-pona":"a","dg-publish":true,"dg-path":"Slovura Roots/a.md","permalink":"/slovura-roots/a/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"emphasis, confirmation","origin":"(toki pona) a","toki-pona":"a"}}
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

