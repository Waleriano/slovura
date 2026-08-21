---
{"meaning":"country, state","logic":"land of a group","roots":["[[ma]]","[[kru]]"],"tags":["slovura"],"dg-publish":true,"dg-path":"Slovura Words/makru.md","permalink":"/slovura-words/makru/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"country, state","logic":"land of a group","roots":["[[Projects/Languages/Slovura/Slovura Roots/ma]]","[[Projects/Languages/Slovura/Slovura Roots/kru]]"],"tags":["slovura"]}}
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
    name: WordRoots
    filters:
      and:
        - this.roots.Contains(file.asLink())
    order:
      - file.name
      - meaning

```

