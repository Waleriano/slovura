---
{"meaning":"paste, powder","origin":"(English) fluid","toki-pona":"ko","dg-publish":true,"dg-path":"Slovura Roots/flu.md","permalink":"/slovura-roots/flu/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"paste, powder","origin":"(English) fluid","toki-pona":"ko"}}
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

