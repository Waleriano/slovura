---
{"meaning":"grain, cereal, bread, pasta","origin":"(Czech) chleba","toki-pona":"pan","dg-publish":true,"dg-path":"Slovura Roots/kle.md","permalink":"/slovura-roots/kle/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"grain, cereal, bread, pasta","origin":"(Czech) chleba","toki-pona":"pan"}}
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

