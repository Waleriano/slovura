---
{"meaning":"medicine, cure","origin":"(English) cure","toki-pona":"misikeke","dg-publish":true,"dg-path":"Slovura Roots/xu.md","permalink":"/slovura-roots/xu/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"medicine, cure","origin":"(English) cure","toki-pona":"misikeke"}}
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

