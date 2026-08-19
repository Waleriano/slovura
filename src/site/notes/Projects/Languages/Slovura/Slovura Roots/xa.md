---
{"meaning":"extra, additional, spice","origin":"(English) extra","toki-pona":"namako","dg-publish":true,"dg-path":"Slovura Roots/xa.md","permalink":"/slovura-roots/xa/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"extra, additional, spice","origin":"(English) extra","toki-pona":"namako"}}
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

