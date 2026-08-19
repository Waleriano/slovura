---
{"meaning":"parent, creator","origin":"(English) parent","toki-pona":"mama","dg-publish":true,"dg-path":"Slovura Roots/pa.md","permalink":"/slovura-roots/pa/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"parent, creator","origin":"(English) parent","toki-pona":"mama"}}
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

