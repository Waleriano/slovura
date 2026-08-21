---
{"meaning":"new, fresh, another","origin":"(English) fresh","toki-pona":"sin","dg-publish":true,"dg-path":"Slovura Roots/fre.md","permalink":"/slovura-roots/fre/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"new, fresh, another","origin":"(English) fresh","toki-pona":"sin"}}
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

