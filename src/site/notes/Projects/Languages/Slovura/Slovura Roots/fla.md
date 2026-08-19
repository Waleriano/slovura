---
{"meaning":"long hard object (rod, stick)","origin":"(Czech) flákanec","toki-pona":"palisa","dg-publish":true,"dg-path":"Slovura Roots/fla.md","permalink":"/slovura-roots/fla/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"long hard object (rod, stick)","origin":"(Czech) flákanec","toki-pona":"palisa"}}
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

