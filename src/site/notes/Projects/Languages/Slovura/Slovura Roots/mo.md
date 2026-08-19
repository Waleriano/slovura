---
{"meaning":"eat, consume, food","origin":"(toki pona) moku","toki-pona":"moku","dg-publish":true,"dg-path":"Slovura Roots/mo.md","permalink":"/slovura-roots/mo/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"eat, consume, food","origin":"(toki pona) moku","toki-pona":"moku"}}
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

