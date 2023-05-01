---
type: faction
faction: 
location: The Rock of Bral
world: Pieces of Fate
campaign: Pieces of Fate
date: 2023-03-19
description: "A gang on The Rock of Bral"
species: 
gender: 
class: 
status:
aliases:
---
[[ttrpgs/Pieces of Fate/000 World Index|home]]
# [[Sandyfoot Gang]]

## Information
- Led by [[Meredin Sandyfoot]]

## Members
```dataview
list
from "ttrpgs/Pieces of Fate"
where contains(type,"PC") AND econtains(faction,"Sandyfoot Gang")
```

## Referenced in Sessions:

```dataview
table campaign as "Campaign"
from [[Sandyfoot Gang]]
where econtains(type,"session")
sort campaign asc
sort asc
```