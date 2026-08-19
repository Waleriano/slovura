---
{"meaning":"come, become","origin":"(Czech) přijít","toki-pona":"kama","dg-publish":true,"dg-path":"Slovura Roots/pri.md","permalink":"/slovura-roots/pri/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"come, become","origin":"(Czech) přijít","toki-pona":"kama"}}
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

