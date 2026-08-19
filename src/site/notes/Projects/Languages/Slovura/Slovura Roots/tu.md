---
{"meaning":"you","origin":"(Czech) ty, (German) du","toki-pona":"sina","dg-publish":true,"dg-path":"Slovura Roots/tu.md","permalink":"/slovura-roots/tu/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"you","origin":"(Czech) ty, (German) du","toki-pona":"sina"}}
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

