---
{"meaning":"monster, fear, danger, scary","origin":"(English) scary","toki-pona":"monsuta","dg-publish":true,"dg-path":"Slovura Roots/ske.md","permalink":"/slovura-roots/ske/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"monster, fear, danger, scary","origin":"(English) scary","toki-pona":"monsuta"}}
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

