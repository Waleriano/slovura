---
{"meaning":"make, activity, work, project","origin":"(Czech) foch, fortel","toki-pona":"pali","dg-publish":true,"dg-path":"Slovura Roots/fo.md","permalink":"/slovura-roots/fo/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"make, activity, work, project","origin":"(Czech) foch, fortel","toki-pona":"pali"}}
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

