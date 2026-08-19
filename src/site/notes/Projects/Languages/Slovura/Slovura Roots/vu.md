---
{"meaning":"cut, divide, part","origin":"(English) divulsion","toki-pona":"kipisi","dg-publish":true,"dg-path":"Slovura Roots/vu.md","permalink":"/slovura-roots/vu/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"cut, divide, part","origin":"(English) divulsion","toki-pona":"kipisi"}}
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

