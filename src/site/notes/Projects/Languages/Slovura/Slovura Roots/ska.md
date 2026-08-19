---
{"meaning":"high, up, above, jump, sacred","origin":"(Czech) skákat, (English) sky","toki-pona":"sewi","dg-publish":true,"dg-path":"Slovura Roots/ska.md","permalink":"/slovura-roots/ska/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"high, up, above, jump, sacred","origin":"(Czech) skákat, (English) sky","toki-pona":"sewi"}}
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

