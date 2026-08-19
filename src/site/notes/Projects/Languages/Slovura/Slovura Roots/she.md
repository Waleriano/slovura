---
{"meaning":"air, spirit","origin":"(Czech) duše","toki-pona":"kon","dg-publish":true,"dg-path":"Slovura Roots/she.md","permalink":"/slovura-roots/she/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"air, spirit","origin":"(Czech) duše","toki-pona":"kon"}}
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

