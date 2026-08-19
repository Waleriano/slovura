---
{"meaning":"group, community","origin":"(English) group","toki-pona":"kulupu","dg-publish":true,"dg-path":"Slovura Roots/kru.md","permalink":"/slovura-roots/kru/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"group, community","origin":"(English) group","toki-pona":"kulupu"}}
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

