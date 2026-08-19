---
{"meaning":"end, finish, stop, past","origin":"(English) finish","toki-pona":"pini","dg-publish":true,"dg-path":"Slovura Roots/fi.md","permalink":"/slovura-roots/fi/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"end, finish, stop, past","origin":"(English) finish","toki-pona":"pini"}}
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

