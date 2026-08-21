---
{"meaning":"[[Kenku]]","logic":"person + bird","roots":["[[ka]]","[[fli]]"],"tags":["slovura","RPG"],"dg-publish":true,"dg-path":"Slovura Words/kafli.md","permalink":"/slovura-words/kafli/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"[[Kenku]]","logic":"person + bird","roots":["[[Projects/Languages/Slovura/Slovura Roots/ka]]","[[Projects/Languages/Slovura/Slovura Roots/fli]]"],"tags":["slovura","RPG"]}}
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

