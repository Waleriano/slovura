---
{"meaning":"bird, winged animal","origin":"(English) fly","toki-pona":"waso","dg-publish":true,"dg-path":"Slovura Roots/fli.md","permalink":"/slovura-roots/fli/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"bird, winged animal","origin":"(English) fly","toki-pona":"waso"}}
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

