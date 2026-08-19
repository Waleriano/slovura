---
{"meaning":"say, speech, language","origin":"(Czech) slovo","toki-pona":"toki","dg-publish":true,"dg-path":"Slovura Roots/slo.md","permalink":"/slovura-roots/slo/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"say, speech, language","origin":"(Czech) slovo","toki-pona":"toki"}}
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

