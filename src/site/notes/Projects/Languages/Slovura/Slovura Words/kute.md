---
{"meaning":"colourful","logic":"colour + many","roots":["[[ku]]","[[te]]"],"tags":["slovura","colour"],"dg-publish":true,"dg-path":"Slovura Words/kute.md","permalink":"/slovura-words/kute/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"colourful","logic":"colour + many","roots":["[[Projects/Languages/Slovura/Slovura Roots/ku]]","[[Projects/Languages/Slovura/Slovura Roots/te]]"],"tags":["slovura","colour"]}}
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

