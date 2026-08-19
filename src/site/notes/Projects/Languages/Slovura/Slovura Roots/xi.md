---
{"meaning":"halve","origin":"(Greek) schism","toki-pona":"tu","dg-publish":true,"dg-path":"Slovura Roots/xi.md","permalink":"/slovura-roots/xi/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"halve","origin":"(Greek) schism","toki-pona":"tu"}}
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

