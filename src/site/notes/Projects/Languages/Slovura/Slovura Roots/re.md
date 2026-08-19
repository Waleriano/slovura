---
{"meaning":"repeat, times","origin":"(English) repeat","toki-pona":null,"dg-publish":true,"dg-path":"Slovura Roots/re.md","permalink":"/slovura-roots/re/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"repeat, times","origin":"(English) repeat","toki-pona":null}}
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

