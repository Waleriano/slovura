---
{"meaning":"outside, surface, skin, boundary","origin":"(Czech) plocha","toki-pona":"selo","dg-publish":true,"dg-path":"Slovura Roots/plo.md","permalink":"/slovura-roots/plo/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"outside, surface, skin, boundary","origin":"(Czech) plocha","toki-pona":"selo"}}
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

