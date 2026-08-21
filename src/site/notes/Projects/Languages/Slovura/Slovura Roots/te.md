---
{"meaning":"many, very, much, more","origin":"(toki pona) mute","toki-pona":"mute","dg-publish":true,"dg-path":"Slovura Roots/te.md","permalink":"/slovura-roots/te/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"many, very, much, more","origin":"(toki pona) mute","toki-pona":"mute"}}
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

