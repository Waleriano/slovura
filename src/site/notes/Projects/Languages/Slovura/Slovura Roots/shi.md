---
{"meaning":"flat object, paper, document","origin":"(English) sheet","toki-pona":"lipu","dg-publish":true,"dg-path":"Slovura Roots/shi.md","permalink":"/slovura-roots/shi/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"flat object, paper, document","origin":"(English) sheet","toki-pona":"lipu"}}
---


```base
properties:
  file.name:
    displayName: Word
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
      - file.name
      - meaning
      - logic
    columnSize:
      file.name: 84

```

