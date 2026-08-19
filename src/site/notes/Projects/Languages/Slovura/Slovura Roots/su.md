---
{"meaning":"sun, light","origin":"(English) sun","toki-pona":"suno","dg-publish":true,"dg-path":"Slovura Roots/su.md","permalink":"/slovura-roots/su/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"sun, light","origin":"(English) sun","toki-pona":"suno"}}
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

