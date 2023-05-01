---
type: faction
faction: 
location: 
world: Pieces of Fate
campaign: Pieces of Fate
date: 2023-03-21
description: "the name for the PCs and their companions"
species: 
gender: 
class: 
status:
aliases: [The Fools]
---
[[ttrpgs/Pieces of Fate/000 World Index|home]]
# [[The Fools Errant]]

## Information

## Members
```dataview
list
from "ttrpgs/Pieces of Fate"
where contains(type,"PC") AND econtains(faction,"The Fools Errant")
```

## Referenced in Sessions:

```dataview
table campaign as "Campaign"
from [[The Fools Errant]]
where econtains(type,"session")
sort campaign asc
sort asc
```