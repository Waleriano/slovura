---
{"meaning":"pink","logic":"colour + body","roots":["[[ku]]","[[tru]]"],"tags":["slovura","colour"],"dg-publish":true,"dg-path":"Slovura Words/kutru.md","permalink":"/slovura-words/kutru/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"pink","logic":"colour + body","roots":["[[Projects/Languages/Slovura/Slovura Roots/ku]]","[[Projects/Languages/Slovura/Slovura Roots/tru]]"],"tags":["slovura","colour"]}}
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

