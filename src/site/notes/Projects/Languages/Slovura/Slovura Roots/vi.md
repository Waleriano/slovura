---
{"meaning":"want, need, desire, must","origin":"(German) will","toki-pona":"wile","dg-publish":true,"dg-path":"Slovura Roots/vi.md","permalink":"/slovura-roots/vi/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"want, need, desire, must","origin":"(German) will","toki-pona":"wile"}}
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

