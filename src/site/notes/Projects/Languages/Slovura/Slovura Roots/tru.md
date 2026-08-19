---
{"meaning":"body, physical state, torso","origin":"(Czech) trup","toki-pona":"sijelo","dg-publish":true,"dg-path":"Slovura Roots/tru.md","permalink":"/slovura-roots/tru/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"body, physical state, torso","origin":"(Czech) trup","toki-pona":"sijelo"}}
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

