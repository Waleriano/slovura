---
{"meaning":"family","logic":"group + parenthood","roots":["[[kru]]","[[pa]]"],"tags":["slovura"],"dg-publish":true,"dg-path":"Slovura Words/krupa.md","permalink":"/slovura-words/krupa/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"family","logic":"group + parenthood","roots":["[[Projects/Languages/Slovura/Slovura Roots/kru]]","[[Projects/Languages/Slovura/Slovura Roots/pa]]"],"tags":["slovura"]}}
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

