---
{"meaning":"big, tall, long, important, adult, to matter, to care","origin":"(Czech) starý","toki-pona":"suli","dg-publish":true,"dg-path":"Slovura Roots/sta.md","permalink":"/slovura-roots/sta/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"big, tall, long, important, adult, to matter, to care","origin":"(Czech) starý","toki-pona":"suli"}}
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

