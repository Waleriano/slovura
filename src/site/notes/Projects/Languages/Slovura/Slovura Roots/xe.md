---
{"meaning":"different, other","origin":"(Greek) xénos","toki-pona":"ante","dg-publish":true,"dg-path":"Slovura Roots/xe.md","permalink":"/slovura-roots/xe/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"different, other","origin":"(Greek) xénos","toki-pona":"ante"}}
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

