---
{"meaning":"blood, wound","origin":"(Czech) krev","toki-pona":null,"dg-publish":true,"dg-path":"Slovura Roots/kri.md","permalink":"/slovura-roots/kri/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"blood, wound","origin":"(Czech) krev","toki-pona":null}}
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

