---
{"meaning":"hard, solid, stone","origin":"(English) stone","toki-pona":"kiwen","dg-publish":true,"dg-path":"Slovura Roots/sto.md","permalink":"/slovura-roots/sto/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"hard, solid, stone","origin":"(English) stone","toki-pona":"kiwen"}}
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

