---
{"meaning":"conflict, battle, fight, compete","origin":"(English) fight","toki-pona":"utala","dg-publish":true,"dg-path":"Slovura Roots/fra.md","permalink":"/slovura-roots/fra/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"conflict, battle, fight, compete","origin":"(English) fight","toki-pona":"utala"}}
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

