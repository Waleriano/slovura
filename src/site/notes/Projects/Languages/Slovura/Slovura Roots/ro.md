---
{"meaning":"good, simple, useful","origin":"(Czech) dobro","toki-pona":"pona","dg-publish":true,"dg-path":"Slovura Roots/ro.md","permalink":"/slovura-roots/ro/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"good, simple, useful","origin":"(Czech) dobro","toki-pona":"pona"}}
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

