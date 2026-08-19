---
{"meaning":"shame, guilt, apologize","origin":"(Czech) škoda","toki-pona":"apeja","dg-publish":true,"dg-path":"Slovura Roots/shko.md","permalink":"/slovura-roots/shko/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"shame, guilt, apologize","origin":"(Czech) škoda","toki-pona":"apeja"}}
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

