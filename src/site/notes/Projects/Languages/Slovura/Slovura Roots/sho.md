---
{"meaning":"small, little, young","origin":"(English) short","toki-pona":"lili","dg-publish":true,"dg-path":"Slovura Roots/sho.md","permalink":"/slovura-roots/sho/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"small, little, young","origin":"(English) short","toki-pona":"lili"}}
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

