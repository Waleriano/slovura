---
{"meaning":"eye, see, look at","origin":"(English) look","toki-pona":"lukin","dg-publish":true,"dg-path":"Slovura Roots/lu.md","permalink":"/slovura-roots/lu/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"eye, see, look at","origin":"(English) look","toki-pona":"lukin"}}
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

