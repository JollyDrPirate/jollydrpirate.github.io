---
type: faction
faction: 
location: The Rock of Bral
world: Pieces of Fate
campaign: Pieces of Fate
date: 2023-03-20
description: ""
species: 
gender: 
class: 
status:
aliases: [Red Masks, Masks]
---
[[ttrpgs/Pieces of Fate/000 World Index|home]]
# [[The Red Masks]]

## Information
- Although they used to be their own group, [[Ozamata]] has absorbed them into his empl0y, and now is their leader

## Members
```dataview
list
from "ttrpgs/Pieces of Fate"
where contains(type,"PC") AND econtains(faction,"The Red Masks")
```

## Referenced in Sessions:

```dataview
table campaign as "Campaign"
from [[The Red Masks]]
where econtains(type,"session")
sort campaign asc
sort asc
```