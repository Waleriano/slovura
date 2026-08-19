---
{"meaning":"woman, female, feminine","origin":"(Spanish) -na","toki-pona":"meli","dg-publish":true,"dg-path":"Slovura Roots/na.md","permalink":"/slovura-roots/na/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"woman, female, feminine","origin":"(Spanish) -na","toki-pona":"meli"}}
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

