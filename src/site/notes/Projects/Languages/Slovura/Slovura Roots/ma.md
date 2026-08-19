---
{"meaning":"land, earth, country","origin":"(toki pona) ma","toki-pona":"ma","dg-publish":true,"dg-path":"Slovura Roots/ma.md","permalink":"/slovura-roots/ma/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"land, earth, country","origin":"(toki pona) ma","toki-pona":"ma"}}
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

