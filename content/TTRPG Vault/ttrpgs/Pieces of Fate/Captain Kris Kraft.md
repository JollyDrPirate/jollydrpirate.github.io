---
type: NPC
faction: 
location: space.wildspace
world: Pieces of Fate
campaign: Pieces of Fate
date: 2022-12-27
description: "grifter the PCs encountered in Wildspace"
species: Hadozee
gender: male
class: 
aliases:
---
[[000 World Index|home]]
# [[Captain Kris Kraft]]

- Veracity of these facts has not been verified
	- Grew up in the Citadel
	- adopted by humans
	- attended the Spelljammer Academy, graduating in the year 211
		- 20-30 years prior to [[000 World Index|the PCs]]
- First encounter with [[000 World Index|the PCs]]
	- Hailed the [[Diversity]] while spelljamming
	- tried to trick [[000 World Index|the PCs]] into paying phony fines for no registration

## Met in Sessions:
```dataview
table campaign as "Campaign", summary as "Summary"
from [[Captain Kris Kraft]]
where econtains(type,"session")
sort campaign asc
sort asc
```