---
{"meaning":"brown","logic":"colour + ground","roots":["[[ku]]","[[ma]]"],"tags":["slovura","colour"],"dg-publish":true,"dg-path":"Slovura Words/kuma.md","permalink":"/slovura-words/kuma/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"brown","logic":"colour + ground","roots":["[[Projects/Languages/Slovura/Slovura Roots/ku]]","[[Projects/Languages/Slovura/Slovura Roots/ma]]"],"tags":["slovura","colour"]}}
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

