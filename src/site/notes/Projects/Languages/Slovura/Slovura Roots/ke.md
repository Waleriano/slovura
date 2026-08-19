---
{"meaning":"bad, superfluous","origin":"(Czech) kekeš","toki-pona":"ike","dg-publish":true,"dg-path":"Slovura Roots/ke.md","permalink":"/slovura-roots/ke/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"bad, superfluous","origin":"(Czech) kekeš","toki-pona":"ike"}}
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

