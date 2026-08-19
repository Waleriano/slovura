---
{"meaning":"front, wall, chest, face","origin":"(Latin) pre-","toki-pona":"sinpin","dg-publish":true,"dg-path":"Slovura Roots/pre.md","permalink":"/slovura-roots/pre/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"front, wall, chest, face","origin":"(Latin) pre-","toki-pona":"sinpin"}}
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

