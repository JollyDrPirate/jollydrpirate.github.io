---
type: faction
faction: 
location: Orphea
world: Pieces of Fate
campaign: Pieces of Fate
date: 2022-12-27
description: "members of the Theodellus family and their staff"
species: 
gender: 
class: 
aliases:
---
[[000 World Index|home]]
# [[House Theodellus]]

## Information

## Members
```dataview
list
from "ttrpgs/Pieces of Fate"
where contains(type,"PC") AND econtains(faction,"House Theodellus")
```

## Referenced in Sessions:
```dataview
table campaign as "Campaign", summary as "Summary"
from [[House Theodellus]]
where econtains(type,"session")
sort campaign asc
sort asc
```