---
{"meaning":"give, put, send, emit","origin":"(Czech) pro","toki-pona":"pana","dg-publish":true,"dg-path":"Slovura Roots/pro.md","permalink":"/slovura-roots/pro/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"give, put, send, emit","origin":"(Czech) pro","toki-pona":"pana"}}
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

