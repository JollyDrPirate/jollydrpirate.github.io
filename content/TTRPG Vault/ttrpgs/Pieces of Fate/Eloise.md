---
type: NPC
faction: 
location: Port Royal
world: Pieces of Fate
campaign: Pieces of Fate
date: 2022-12-27
description: "a gruff but friendly waitress at the Rusty Nail"
species: Giff
gender: femail
class: 
aliases:
---
[[000 World Index|home]]
# [[Eloise]]

## Met in Sessions:
```dataview
table campaign as "Campaign", summary as "Summary"
from [[Eloise]]
where econtains(type,"session")
sort campaign asc
sort asc
```