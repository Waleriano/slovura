---
{"meaning":"say, speech, language","origin":"(Czech) slovo","toki-pona":"toki","aliases":["slo"],"dg-publish":true,"dg-path":"Slovura Roots/slovura_root_slo.md","permalink":"/slovura-roots/slovura-root-slo/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"say, speech, language","origin":"(Czech) slovo","toki-pona":"toki","aliases":["slo"]}}
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

