---
{"meaning":"using","origin":"(Latin) schema (method, way)","toki-pona":"kepeken","dg-publish":true,"dg-path":"Slovura Roots/shki.md","permalink":"/slovura-roots/shki/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"using","origin":"(Latin) schema (method, way)","toki-pona":"kepeken"}}
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

