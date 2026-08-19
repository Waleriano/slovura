---
{"meaning":"one, unique, unite","origin":"(toki pona) wan","toki-pona":"wan","dg-publish":true,"dg-path":"Slovura Roots/va.md","permalink":"/slovura-roots/va/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"one, unique, unite","origin":"(toki pona) wan","toki-pona":"wan"}}
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

