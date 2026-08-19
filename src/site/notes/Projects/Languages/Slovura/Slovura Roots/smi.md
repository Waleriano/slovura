---
{"meaning":"leg, foot, base","origin":"(Latin) semita (path, way)","toki-pona":"noka","dg-publish":true,"dg-path":"Slovura Roots/smi.md","permalink":"/slovura-roots/smi/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"leg, foot, base","origin":"(Latin) semita (path, way)","toki-pona":"noka"}}
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

