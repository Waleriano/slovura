---
{"meaning":"picture, image, write, draw","origin":"(Czech) pastelka, (toki pona) sitelen","toki-pona":"sitelen","dg-publish":true,"dg-path":"Slovura Roots/ste.md","permalink":"/slovura-roots/ste/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"picture, image, write, draw","origin":"(Czech) pastelka, (toki pona) sitelen","toki-pona":"sitelen"}}
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

