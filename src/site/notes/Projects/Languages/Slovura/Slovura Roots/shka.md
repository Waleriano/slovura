---
{"meaning":"container, box, bowl","origin":"(Czech) škatule","toki-pona":"poki","dg-publish":true,"dg-path":"Slovura Roots/shka.md","permalink":"/slovura-roots/shka/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"container, box, bowl","origin":"(Czech) škatule","toki-pona":"poki"}}
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

