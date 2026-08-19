---
{"meaning":"can, possible","origin":"(Latin) ratio (method, ability)","toki-pona":"ken","dg-publish":true,"dg-path":"Slovura Roots/ra.md","permalink":"/slovura-roots/ra/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"can, possible","origin":"(Latin) ratio (method, ability)","toki-pona":"ken"}}
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

