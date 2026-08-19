---
{"meaning":"black, dark, shadow","origin":"(Czech) smog","toki-pona":"pimeja","dg-publish":true,"dg-path":"Slovura Roots/smo.md","permalink":"/slovura-roots/smo/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"black, dark, shadow","origin":"(Czech) smog","toki-pona":"pimeja"}}
---


```base
formulas:
  Word: link(file.name, file.name.replace(/slovura_word_/, ""))
properties:
  note.meaning:
    displayName: Meaning
  note.logic:
    displayName: Logic
views:
  - type: table
    name: RootWords
    filters:
      and:
        - roots.Contains(this.file.name)
    order:
      - formula.Word
      - meaning
      - logic

```

