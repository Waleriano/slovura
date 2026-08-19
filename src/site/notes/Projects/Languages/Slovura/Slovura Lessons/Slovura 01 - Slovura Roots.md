---
{"tags":["slovura","lesson"],"sequence":1,"aliases":["roots"],"dg-publish":true,"dg-path":"Slovura Lessons/Slovura 01 - Slovura Roots.md","permalink":"/slovura-lessons/slovura-01-slovura-roots/","dgPassFrontmatter":true,"dg-note-properties":{"tags":["slovura","lesson"],"sequence":1,"aliases":["roots"]}}
---


# [[Projects/Languages/Slovura/Slovura Lessons/Slovura 01 - Slovura Roots\|Slovura 01 - Slovura Roots]]


```base
formulas:
  Root: note.aliases[0]
  prefix: file.name.replace(/slovura_root_/, "").reverse().slice(1).reverse()
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
      - formula.Root
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
