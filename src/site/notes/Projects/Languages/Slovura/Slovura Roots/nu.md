---
{"meaning":"number, quantity, amount","origin":"(Spanish) numero","toki-pona":"nanpa","dg-publish":true,"dg-path":"Slovura Roots/nu.md","permalink":"/slovura-roots/nu/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"number, quantity, amount","origin":"(Spanish) numero","toki-pona":"nanpa"}}
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

