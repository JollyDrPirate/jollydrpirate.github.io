---
type: NPC
faction: House Theodellus
location: Orphea
world: Pieces of Fate
campaign: Pieces of Fate
date: 2022-12-27
description: "butler at the Theodellus family home"
species: Astral Elf
gender: male
class: 
aliases:
---
[[000 World Index|home]]
# [[Jarval]]

## Met in Sessions:
```dataview
table campaign as "Campaign", summary as "Summary"
from [[Jarval]]
where econtains(type,"session")
sort campaign asc
sort asc
```