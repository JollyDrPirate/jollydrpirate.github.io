---
type: faction
faction: 
location: [Orphea, Nee A'bohr]
world: Pieces of Fate
campaign: Pieces of Fate
date: 2022-12-27
description: "worshippers Khot, intent on returning her to the material plane"
species: 
gender: 
class: 
aliases: [Cultists of Khot, cultists]
---
[[000 World Index|home]]
# [[Cult of Khot]]

## Information
- a cult dedicated to the worship of [[Shar|Khot]]
- their goal is to return [[Shar|Khot]] to the material plane
	- her current location is unclear
- previous attempts to return her resulted in the destruction of [[Yazir]]

## Members
```dataview
list
from "ttrpgs/Pieces of Fate"
where contains(type,"PC") AND econtains(faction,"Cult of Khot")
```

## Referenced in Sessions:
```dataview
table campaign as "Campaign", summary as "Summary"
from [[Cult of Khot]]
where econtains(type,"session")
sort campaign asc
sort asc
```