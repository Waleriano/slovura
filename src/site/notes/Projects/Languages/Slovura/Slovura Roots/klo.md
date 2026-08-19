---
{"meaning":"hunt, search","origin":"(Czech) klovat","toki-pona":"alasa","dg-publish":true,"dg-path":"Slovura Roots/klo.md","permalink":"/slovura-roots/klo/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"hunt, search","origin":"(Czech) klovat","toki-pona":"alasa"}}
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

