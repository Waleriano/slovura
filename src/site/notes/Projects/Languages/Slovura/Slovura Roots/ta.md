---
{"meaning":"this, that","origin":"(Czech) ta","toki-pona":"ni","dg-publish":true,"dg-path":"Slovura Roots/ta.md","permalink":"/slovura-roots/ta/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"this, that","origin":"(Czech) ta","toki-pona":"ni"}}
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

