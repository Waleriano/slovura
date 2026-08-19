---
{"meaning":"man, male, masculine","origin":"(Spanish) -no","toki-pona":"mije","dg-publish":true,"dg-path":"Slovura Roots/no.md","permalink":"/slovura-roots/no/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"man, male, masculine","origin":"(Spanish) -no","toki-pona":"mije"}}
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

