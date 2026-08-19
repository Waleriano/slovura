---
{"meaning":"no, not, zero","origin":"(Czech) ne","toki-pona":"ala","dg-publish":true,"dg-path":"Slovura Roots/ne.md","permalink":"/slovura-roots/ne/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"no, not, zero","origin":"(Czech) ne","toki-pona":"ala"}}
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

