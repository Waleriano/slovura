---
{"meaning":"all","origin":"(Italian) tutti","toki-pona":"ale","dg-publish":true,"dg-path":"Slovura Roots/ti.md","permalink":"/slovura-roots/ti/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"all","origin":"(Italian) tutti","toki-pona":"ale"}}
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

