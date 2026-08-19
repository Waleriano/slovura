---
{"meaning":"at, in, on, real, true, exist","origin":"(toki pona) lon","toki-pona":"lon","dg-publish":true,"dg-path":"Slovura Roots/lo.md","permalink":"/slovura-roots/lo/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"at, in, on, real, true, exist","origin":"(toki pona) lon","toki-pona":"lon"}}
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

