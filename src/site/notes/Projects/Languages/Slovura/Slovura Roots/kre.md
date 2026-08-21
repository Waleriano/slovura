---
{"meaning":"lizard or reptile","origin":"(Czech) krokodýl","toki-pona":"akesi","dg-publish":true,"dg-path":"Slovura Roots/kre.md","permalink":"/slovura-roots/kre/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"lizard or reptile","origin":"(Czech) krokodýl","toki-pona":"akesi"}}
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

