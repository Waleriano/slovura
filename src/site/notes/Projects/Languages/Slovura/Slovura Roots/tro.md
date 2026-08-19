---
{"meaning":"sound, noise","origin":"(Czech) troubit","toki-pona":"kalama","dg-publish":true,"dg-path":"Slovura Roots/tro.md","permalink":"/slovura-roots/tro/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"sound, noise","origin":"(Czech) troubit","toki-pona":"kalama"}}
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

