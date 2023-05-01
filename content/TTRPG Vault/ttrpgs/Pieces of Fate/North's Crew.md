---
type: faction
faction: 
location: 
world: Pieces of Fate
campaign: Pieces of Fate
date: 2022-12-27
description: "members of Captain George North's crew"
species: 
gender: 
class: 
aliases:
---
[[000 World Index|home]]
# [[North's Crew]]

## Information

## Members
```dataview
list
from "ttrpgs/Pieces of Fate"
where contains(type,"PC") AND econtains(faction,"North's Crew")
```

## Referenced in Sessions:
```dataview
table campaign as "Campaign", summary as "Summary"
from [[North's Crew]]
where econtains(type,"session")
sort campaign asc
sort asc
```
