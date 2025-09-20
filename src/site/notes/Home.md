---
{"dg-publish":true,"permalink":"/home/","tags":["gardenEntry"]}
---

# Maple's RUMBLE Vault

w.i.p



```base
properties:
  file.folder:
    displayName: Type
views:
  - type: cards
    name: Gallery
    filters:
      or:
        - file.inFolder("Combo")
        - file.inFolder("Player")
        - file.inFolder("Fact")
    order:
      - file.name
      - file.folder
    sort:
      - property: file.folder
        direction: DESC
    image: note.Image
    cardSize: 200
    imageAspectRatio: 1
    imageFit: ""

```