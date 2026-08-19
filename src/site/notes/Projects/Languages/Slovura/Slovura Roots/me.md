---
{"meaning":"have, hold, own","origin":"(Czech) mít","toki-pona":"jo","dg-publish":true,"dg-path":"Slovura Roots/me.md","permalink":"/slovura-roots/me/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"have, hold, own","origin":"(Czech) mít","toki-pona":"jo"}}
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

