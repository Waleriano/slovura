---
{"meaning":"nation","logic":"group of a land","roots":["[[kru]]","[[ma]]"],"tags":["slovura"],"dg-publish":true,"dg-path":"Slovura Words/kruma.md","permalink":"/slovura-words/kruma/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"nation","logic":"group of a land","roots":["[[Projects/Languages/Slovura/Slovura Roots/kru]]","[[Projects/Languages/Slovura/Slovura Roots/ma]]"],"tags":["slovura"]}}
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

