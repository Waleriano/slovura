---
{"meaning":"and (used between multiple subjects)","origin":"(Czech) i","toki-pona":"en","dg-publish":true,"dg-path":"Slovura Roots/i.md","permalink":"/slovura-roots/i/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"and (used between multiple subjects)","origin":"(Czech) i","toki-pona":"en"}}
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

