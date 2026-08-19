---
{"meaning":"I, me, we, us","origin":"(toki pona) mi","toki-pona":"mi","dg-publish":true,"dg-path":"Slovura Roots/mi.md","permalink":"/slovura-roots/mi/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"I, me, we, us","origin":"(toki pona) mi","toki-pona":"mi"}}
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

