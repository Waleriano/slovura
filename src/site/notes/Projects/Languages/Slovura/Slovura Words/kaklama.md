---
{"meaning":"king, emperor","logic":"person + lead + land","roots":["[[ka]]","[[kla]]","[[ma]]"],"tags":["slovura"],"dg-publish":true,"dg-path":"Slovura Words/kaklama.md","permalink":"/slovura-words/kaklama/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"king, emperor","logic":"person + lead + land","roots":["[[Projects/Languages/Slovura/Slovura Roots/ka]]","[[Projects/Languages/Slovura/Slovura Roots/kla]]","[[Projects/Languages/Slovura/Slovura Roots/ma]]"],"tags":["slovura"]}}
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

