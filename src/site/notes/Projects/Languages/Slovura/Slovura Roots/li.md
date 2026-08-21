---
{"meaning":"(predicate marker)","origin":"(toki pona) li","toki-pona":"li","dg-publish":true,"dg-path":"Slovura Roots/li.md","permalink":"/slovura-roots/li/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"(predicate marker)","origin":"(toki pona) li","toki-pona":"li"}}
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

