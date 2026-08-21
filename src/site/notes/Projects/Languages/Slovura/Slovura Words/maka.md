---
{"meaning":"city, town, village","logic":"land of people","roots":["[[ma]]","[[ka]]"],"tags":["slovura"],"dg-publish":true,"dg-path":"Slovura Words/maka.md","permalink":"/slovura-words/maka/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"city, town, village","logic":"land of people","roots":["[[Projects/Languages/Slovura/Slovura Roots/ma]]","[[Projects/Languages/Slovura/Slovura Roots/ka]]"],"tags":["slovura"]}}
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

