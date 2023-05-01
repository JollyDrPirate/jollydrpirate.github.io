---
type: NPC
faction: 
location: 
world: Pieces of Fate
campaign: Pieces of Fate
date: 2022-12-27
description: "Bio Electric Navigator - 'Jammer Integrated aboard the Diversity"
species: Autognome
gender: none
class: 
aliases:
---
[[000 World Index|home]]
# [[BENJI]]

BENJI = Bio Electric Navigator - 'Jammer Integrated

## Met in Sessions:
```dataview
table campaign as "Campaign", summary as "Summary"
from [[BENJI]]
where econtains(type,"session")
sort campaign asc
sort asc
```