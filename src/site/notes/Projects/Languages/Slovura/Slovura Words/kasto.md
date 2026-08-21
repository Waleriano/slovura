---
{"meaning":"[[Dwarf]]","logic":"person + stone","roots":["[[ka]]","[[sto]]"],"tags":["slovura","RPG"],"dg-publish":true,"dg-path":"Slovura Words/kasto.md","permalink":"/slovura-words/kasto/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"[[RPG/Characters/Race/Dwarf]]","logic":"person + stone","roots":["[[Projects/Languages/Slovura/Slovura Roots/ka]]","[[Projects/Languages/Slovura/Slovura Roots/sto]]"],"tags":["slovura","RPG"]}}
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

