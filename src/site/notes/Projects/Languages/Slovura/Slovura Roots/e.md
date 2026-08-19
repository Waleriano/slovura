---
{"meaning":"direct object marker","origin":"(toki pona) e","toki-pona":"e","dg-publish":true,"dg-path":"Slovura Roots/e.md","permalink":"/slovura-roots/e/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"direct object marker","origin":"(toki pona) e","toki-pona":"e"}}
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

