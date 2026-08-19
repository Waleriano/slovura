---
{"meaning":"but, only","origin":"(Czech) kromě","toki-pona":"taso","dg-publish":true,"dg-path":"Slovura Roots/kro.md","permalink":"/slovura-roots/kro/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"but, only","origin":"(Czech) kromě","toki-pona":"taso"}}
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

