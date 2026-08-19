---
{"meaning":"of, who, (order modifier)","origin":"(toki pona) pi","toki-pona":"pi","dg-publish":true,"dg-path":"Slovura Roots/pi.md","permalink":"/slovura-roots/pi/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"of, who, (order modifier)","origin":"(toki pona) pi","toki-pona":"pi"}}
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

