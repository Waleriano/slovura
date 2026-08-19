---
{"meaning":"fish, sea creature","origin":"(Czech) plout","toki-pona":"kala","dg-publish":true,"dg-path":"Slovura Roots/plu.md","permalink":"/slovura-roots/plu/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"fish, sea creature","origin":"(Czech) plout","toki-pona":"kala"}}
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

