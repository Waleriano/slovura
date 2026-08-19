---
{"meaning":"false, fake, deceptive","origin":"(Czech) plivat","toki-pona":"powe","dg-publish":true,"dg-path":"Slovura Roots/pli.md","permalink":"/slovura-roots/pli/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"false, fake, deceptive","origin":"(Czech) plivat","toki-pona":"powe"}}
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

