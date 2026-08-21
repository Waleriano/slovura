---
{"meaning":"inside, stomach","origin":"(Greek) mesos","toki-pona":"insa","dg-publish":true,"dg-path":"Slovura Roots/sme.md","permalink":"/slovura-roots/sme/","dgPassFrontmatter":true,"dg-note-properties":{"meaning":"inside, stomach","origin":"(Greek) mesos","toki-pona":"insa"}}
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

