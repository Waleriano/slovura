---
{"meaning":"feelings, emotion, heart","origin":"(English) feeling","toki-pona":"pilin","dg-publish":true,"dg-path":"Slovura Roots/fe.md","permalink":"/slovura-roots/fe/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"feelings, emotion, heart","origin":"(English) feeling","toki-pona":"pilin"}}
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

