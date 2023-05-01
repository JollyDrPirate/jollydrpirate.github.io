---
type: faction
faction: 
location: 
world: Pieces of Fate
campaign: Pieces of Fate
date: 2023-01-25
description: "the leaders of the various gangs of The Rock of Bral"
species: 
gender: 
class: 
status:
aliases: [Underbarron]
---
[[ttrpgs/Pieces of Fate/000 World Index|home]]
# [[Underbarrons]]

## Information

## Members
```dataview
list
from "ttrpgs/Pieces of Fate"
where contains(type,"PC") AND econtains(faction,"Underbarrons")
```

## Referenced in Sessions:

```dataview
table campaign as "Campaign"
from [[Underbarrons]]
where econtains(type,"session")
sort campaign asc
sort asc
```