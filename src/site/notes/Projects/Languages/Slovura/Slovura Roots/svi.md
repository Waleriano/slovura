---
{"meaning":"sweet, cute, sugar","origin":"(English) sweet","toki-pona":"suwi","dg-publish":true,"dg-path":"Slovura Roots/svi.md","permalink":"/slovura-roots/svi/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"sweet, cute, sugar","origin":"(English) sweet","toki-pona":"suwi"}}
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

