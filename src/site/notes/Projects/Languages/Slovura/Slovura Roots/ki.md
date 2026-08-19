---
{"meaning":"strong, power, energy","origin":"(D&D) ki","toki-pona":"wawa","dg-publish":true,"dg-path":"Slovura Roots/ki.md","permalink":"/slovura-roots/ki/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"strong, power, energy","origin":"(D&D) ki","toki-pona":"wawa"}}
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

