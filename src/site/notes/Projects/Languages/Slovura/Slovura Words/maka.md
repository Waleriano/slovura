---
{"meaning":"city, town, village","logic":"land of people","roots":["[[ma]]","[[ka]]"],"tags":["slovura"],"dg-publish":true,"dg-path":"Slovura Words/maka.md","permalink":"/slovura-words/maka/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"city, town, village","logic":"land of people","roots":["[[Projects/Languages/Slovura/Slovura Roots/ma]]","[[Projects/Languages/Slovura/Slovura Roots/ka]]"],"tags":["slovura"]}}
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

