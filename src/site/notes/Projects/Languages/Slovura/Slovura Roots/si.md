---
{"meaning":"circle, wheel, ball, year","origin":"(English) circle","toki-pona":"sike","dg-publish":true,"dg-path":"Slovura Roots/si.md","permalink":"/slovura-roots/si/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"circle, wheel, ball, year","origin":"(English) circle","toki-pona":"sike"}}
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

