---
{"meaning":"house, building, room","origin":"(English) place","toki-pona":"tomo","dg-publish":true,"dg-path":"Slovura Roots/pla.md","permalink":"/slovura-roots/pla/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"house, building, room","origin":"(English) place","toki-pona":"tomo"}}
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

