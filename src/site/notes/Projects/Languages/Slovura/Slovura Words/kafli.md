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
    name: WordRoots
    filters:
      and:
        - this.roots.Contains(file.asLink())
    order:
      - file.name
      - meaning

```

