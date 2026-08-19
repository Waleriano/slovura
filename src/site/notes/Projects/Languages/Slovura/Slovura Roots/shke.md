---
{"meaning":"strange, silly, drunk","origin":"(Czech) šašek","toki-pona":"nasa","dg-publish":true,"dg-path":"Slovura Roots/shke.md","permalink":"/slovura-roots/shke/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"strange, silly, drunk","origin":"(Czech) šašek","toki-pona":"nasa"}}
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

