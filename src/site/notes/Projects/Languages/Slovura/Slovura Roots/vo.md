---
{"meaning":"water, liquid, wet, wash","origin":"(Czech) voda","toki-pona":"telo","dg-publish":true,"dg-path":"Slovura Roots/vo.md","permalink":"/slovura-roots/vo/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"water, liquid, wet, wash","origin":"(Czech) voda","toki-pona":"telo"}}
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

