---
{"meaning":"person, human","origin":"(Stephen King - Dark Tower) Ka","toki-pona":"jan","dg-publish":true,"dg-path":"Slovura Roots/ka.md","permalink":"/slovura-roots/ka/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"person, human","origin":"(Stephen King - Dark Tower) Ka","toki-pona":"jan"}}
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

