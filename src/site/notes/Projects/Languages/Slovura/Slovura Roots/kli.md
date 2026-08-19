---
{"meaning":"dead, die, death, kill","origin":"(English) kill","toki-pona":"moli","dg-publish":true,"dg-path":"Slovura Roots/kli.md","permalink":"/slovura-roots/kli/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"dead, die, death, kill","origin":"(English) kill","toki-pona":"moli"}}
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

