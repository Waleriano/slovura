---
{"meaning":"emphasis, confirmation","origin":"(toki pona) a","toki-pona":"a","dg-publish":true,"dg-path":"Slovura Roots/a.md","permalink":"/slovura-roots/a/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"emphasis, confirmation","origin":"(toki pona) a","toki-pona":"a"}}
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

