---
{"meaning":"same, similar, equal, like","origin":"(English) same","toki-pona":"sama","dg-publish":true,"dg-path":"Slovura Roots/sa.md","permalink":"/slovura-roots/sa/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"same, similar, equal, like","origin":"(English) same","toki-pona":"sama"}}
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

