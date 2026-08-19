---
{"meaning":"from, because of, cause","origin":"(English) from","toki-pona":"tan","dg-publish":true,"dg-path":"Slovura Roots/fro.md","permalink":"/slovura-roots/fro/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"from, because of, cause","origin":"(English) from","toki-pona":"tan"}}
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

