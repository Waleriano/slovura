---
{"meaning":"love, respect","origin":"(Spanish) cariño","toki-pona":"olin","dg-publish":true,"dg-path":"Slovura Roots/ri.md","permalink":"/slovura-roots/ri/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"love, respect","origin":"(Spanish) cariño","toki-pona":"olin"}}
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

