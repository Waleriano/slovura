---
{"meaning":"average, medium","origin":"(French) trans (across, through)","toki-pona":"meso","dg-publish":true,"dg-path":"Slovura Roots/tre.md","permalink":"/slovura-roots/tre/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"average, medium","origin":"(French) trans (across, through)","toki-pona":"meso"}}
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

