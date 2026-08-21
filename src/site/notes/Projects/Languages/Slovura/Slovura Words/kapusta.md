---
{"meaning":"overconfident or indiscreet person","logic":"person + mouth + big","roots":["[[ka]]","[[pu]]","[[sta]]"],"tags":["slovura"],"dg-publish":true,"dg-path":"Slovura Words/kapusta.md","permalink":"/slovura-words/kapusta/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"overconfident or indiscreet person","logic":"person + mouth + big","roots":["[[Projects/Languages/Slovura/Slovura Roots/ka]]","[[Projects/Languages/Slovura/Slovura Roots/pu]]","[[Projects/Languages/Slovura/Slovura Roots/sta]]"],"tags":["slovura"]}}
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

