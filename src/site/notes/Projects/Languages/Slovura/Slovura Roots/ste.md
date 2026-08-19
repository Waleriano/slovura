---
{"meaning":"picture, image, write, draw","origin":"(Czech) pastelka, (toki pona) sitelen","toki-pona":"sitelen","dg-publish":true,"dg-path":"Slovura Roots/ste.md","permalink":"/slovura-roots/ste/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"picture, image, write, draw","origin":"(Czech) pastelka, (toki pona) sitelen","toki-pona":"sitelen"}}
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

