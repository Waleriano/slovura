---
{"meaning":"line, string, hair","origin":"(English) slim","toki-pona":"linja","dg-publish":true,"dg-path":"Slovura Roots/sli.md","permalink":"/slovura-roots/sli/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"line, string, hair","origin":"(English) slim","toki-pona":"linja"}}
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

