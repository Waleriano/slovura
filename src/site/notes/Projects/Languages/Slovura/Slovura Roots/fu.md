---
{"meaning":"away, absent, missing","origin":"(Czech) fuč","toki-pona":"weka","dg-publish":true,"dg-path":"Slovura Roots/fu.md","permalink":"/slovura-roots/fu/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"away, absent, missing","origin":"(Czech) fuč","toki-pona":"weka"}}
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

