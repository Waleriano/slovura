---
{"meaning":"more, after","origin":"(Bulgarian) po","toki-pona":null,"dg-publish":true,"dg-path":"Slovura Roots/po.md","permalink":"/slovura-roots/po/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"more, after","origin":"(Bulgarian) po","toki-pona":null}}
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

