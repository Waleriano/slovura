---
{"meaning":"plant","origin":"(Czech) tráva","toki-pona":"kasi","dg-publish":true,"dg-path":"Slovura Roots/tra.md","permalink":"/slovura-roots/tra/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"plant","origin":"(Czech) tráva","toki-pona":"kasi"}}
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

