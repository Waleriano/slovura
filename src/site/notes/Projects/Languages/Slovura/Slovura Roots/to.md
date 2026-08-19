---
{"meaning":"thing, object, matter","origin":"(Czech) to","toki-pona":"ijo","dg-publish":true,"dg-path":"Slovura Roots/to.md","permalink":"/slovura-roots/to/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"thing, object, matter","origin":"(Czech) to","toki-pona":"ijo"}}
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

