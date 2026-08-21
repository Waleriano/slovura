---
{"meaning":"black","logic":"colour + dark","roots":["[[ku]]","[[smo]]"],"tags":["slovura","colour"],"dg-publish":true,"dg-path":"Slovura Words/kusmo.md","permalink":"/slovura-words/kusmo/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"black","logic":"colour + dark","roots":["[[Projects/Languages/Slovura/Slovura Roots/ku]]","[[Projects/Languages/Slovura/Slovura Roots/smo]]"],"tags":["slovura","colour"]}}
---


```base
formulas:
  prefix: file.name.replace("a","").replace("e","").replace("i","").replace("o","").replace("u","")
properties:
  file.name:
    displayName: Root
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

