---
{"meaning":"animal, land mammal","origin":"(English) mu (cow sound)","toki-pona":"soweli","dg-publish":true,"dg-path":"Slovura Roots/mu.md","permalink":"/slovura-roots/mu/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"animal, land mammal","origin":"(English) mu (cow sound)","toki-pona":"soweli"}}
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

