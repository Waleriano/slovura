---
{"meaning":"sibling","logic":"person + same + parent","roots":["[[ka]]","[[sa]]","[[pa]]"],"tags":["slovura"],"dg-publish":true,"dg-path":"Slovura Words/kasapa.md","permalink":"/slovura-words/kasapa/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"sibling","logic":"person + same + parent","roots":["[[Projects/Languages/Slovura/Slovura Roots/ka]]","[[Projects/Languages/Slovura/Slovura Roots/sa]]","[[Projects/Languages/Slovura/Slovura Roots/pa]]"],"tags":["slovura"]}}
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

