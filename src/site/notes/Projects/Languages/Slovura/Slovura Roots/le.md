---
{"meaning":"he, she, it, they","origin":"(Spanish) le","toki-pona":"ona","dg-publish":true,"dg-path":"Slovura Roots/le.md","permalink":"/slovura-roots/le/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"he, she, it, they","origin":"(Spanish) le","toki-pona":"ona"}}
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

