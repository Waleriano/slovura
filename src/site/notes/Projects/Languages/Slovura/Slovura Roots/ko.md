---
{"meaning":"to, for, move, go","origin":"(English) go","toki-pona":"tawa","dg-publish":true,"dg-path":"Slovura Roots/ko.md","permalink":"/slovura-roots/ko/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"to, for, move, go","origin":"(English) go","toki-pona":"tawa"}}
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

