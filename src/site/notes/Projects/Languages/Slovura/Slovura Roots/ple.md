---
{"meaning":"cloth, clothing, cover, privacy","origin":"(Czech) plena","toki-pona":"len","dg-publish":true,"dg-path":"Slovura Roots/ple.md","permalink":"/slovura-roots/ple/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"cloth, clothing, cover, privacy","origin":"(Czech) plena","toki-pona":"len"}}
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

