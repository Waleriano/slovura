---
{"meaning":"to be the child of, originate from, descendant","origin":"(English) small","toki-pona":null,"dg-publish":true,"dg-path":"Slovura Roots/sma.md","permalink":"/slovura-roots/sma/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"to be the child of, originate from, descendant","origin":"(English) small","toki-pona":null}}
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

