---
{"meaning":"vocative or imperative","origin":"(toki pona) o","toki-pona":"o","dg-publish":true,"dg-path":"Slovura Roots/o.md","permalink":"/slovura-roots/o/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"vocative or imperative","origin":"(toki pona) o","toki-pona":"o"}}
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

