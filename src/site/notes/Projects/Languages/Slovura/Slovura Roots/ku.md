---
{"meaning":"colour, painted","origin":"(English) colourful","toki-pona":"kule","dg-publish":true,"dg-path":"Slovura Roots/ku.md","permalink":"/slovura-roots/ku/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"colour, painted","origin":"(English) colourful","toki-pona":"kule"}}
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
