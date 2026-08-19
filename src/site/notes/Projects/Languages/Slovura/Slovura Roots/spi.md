---
{"meaning":"back, rear","origin":"(Latin) spina","toki-pona":"monsi","dg-publish":true,"dg-path":"Slovura Roots/spi.md","permalink":"/slovura-roots/spi/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"back, rear","origin":"(Latin) spina","toki-pona":"monsi"}}
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

