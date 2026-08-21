---
{"meaning":"blue","logic":"colour + sky","roots":["[[ku]]","[[ska]]"],"tags":["slovura","colour"],"dg-publish":true,"dg-path":"Slovura Words/kuska.md","permalink":"/slovura-words/kuska/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"blue","logic":"colour + sky","roots":["[[Projects/Languages/Slovura/Slovura Roots/ku]]","[[Projects/Languages/Slovura/Slovura Roots/ska]]"],"tags":["slovura","colour"]}}
---


```base
formulas:
  prefix: file.name.replace("a","").replace("e","").replace("i","").replace("o","").replace("u","")
properties:
  note.meaning:
    displayName: Meaning
  note.toki-pona:
    displayName: toki pona
  note.origin:
    displayName: Origin
views:
  - type: table
    name: AllRoots
    filters:
      and:
        - file.inFolder("Projects/Languages/Slovura/Slovura Roots")
    order:
      - file.name
      - meaning
      - toki-pona
      - origin
    sort:
      - property: formula.prefix
        direction: ASC
    columnSize:
      note.meaning: 217
      note.toki-pona: 104
      note.origin: 164

```

