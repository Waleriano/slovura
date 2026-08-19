---
{"meaning":"ear, hear, listen, obey","origin":"(Czech) sluch","toki-pona":"kute","dg-publish":true,"dg-path":"Slovura Roots/slu.md","permalink":"/slovura-roots/slu/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"ear, hear, listen, obey","origin":"(Czech) sluch","toki-pona":"kute"}}
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

