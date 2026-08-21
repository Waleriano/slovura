---
{"meaning":"word, name","origin":"(toki pona) nimi","toki-pona":"nimi","dg-publish":true,"dg-path":"Slovura Roots/ni.md","permalink":"/slovura-roots/ni/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"word, name","origin":"(toki pona) nimi","toki-pona":"nimi"}}
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

