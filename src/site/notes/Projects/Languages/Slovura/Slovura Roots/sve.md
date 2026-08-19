---
{"meaning":"white, light-colored","origin":"(Czech) světlý","toki-pona":"walo","dg-publish":true,"dg-path":"Slovura Roots/sve.md","permalink":"/slovura-roots/sve/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"white, light-colored","origin":"(Czech) světlý","toki-pona":"walo"}}
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

