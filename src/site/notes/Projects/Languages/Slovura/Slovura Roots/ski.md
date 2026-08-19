---
{"meaning":"bump, hill, mountain, nose","origin":"(English) ski","toki-pona":"nena","dg-publish":true,"dg-path":"Slovura Roots/ski.md","permalink":"/slovura-roots/ski/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"bump, hill, mountain, nose","origin":"(English) ski","toki-pona":"nena"}}
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

