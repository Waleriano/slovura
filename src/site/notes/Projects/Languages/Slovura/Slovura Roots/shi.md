---
{"meaning":"flat object, paper, document","origin":"(English) sheet","toki-pona":"lipu","dg-publish":true,"dg-path":"Slovura Roots/shi.md","permalink":"/slovura-roots/shi/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"flat object, paper, document","origin":"(English) sheet","toki-pona":"lipu"}}
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

