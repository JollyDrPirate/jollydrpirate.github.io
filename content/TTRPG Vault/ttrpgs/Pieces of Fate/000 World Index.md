---
title: "The World of the Pieces of Fate"
world: Pieces of Fate
setting: Sam's Spelljammer
campaign: Pieces of Fate
status: active
role: player
system: D&D 5e
type: world
aliases: ["The World of the Pieces of Fate", "PoF Index", "the PCs", "PCs"]
tags:
pin: true
---
# [[000 World Index|The World of the Pieces of Fate]]


## Player Characters

<table class="dataview table-view-table"><thead class="table-view-thead"><tr class="table-view-tr-header"><th class="table-view-th"><span>File</span><span class="dataview small-text">4</span></th><th class="table-view-th"><span>Species</span></th><th class="table-view-th"><span>Class</span></th><th class="table-view-th"><span>Status</span></th><th class="table-view-th"><span>Player</span></th></tr></thead><tbody class="table-view-tbody"><tr><td><span><a data-tooltip-position="top" aria-label="ttrpgs/Pieces of Fate/Alistair Theodellus II.md" data-href="ttrpgs/Pieces of Fate/Alistair Theodellus II.md" href="ttrpgs/Pieces of Fate/Alistair Theodellus II.md" class="internal-link" target="_blank" rel="noopener">Alistair Theodellus II</a></span></td><td><span>Astral Elf</span></td><td><ul class="dataview dataview-ul dataview-result-list-ul"><li class="dataview-result-list-li"><span>Warlock</span></li><li class="dataview-result-list-li"><span>Sorcerer</span></li></ul></td><td><span>active</span></td><td><span>Cody Ihnen</span></td></tr><tr><td><span><a data-tooltip-position="top" aria-label="ttrpgs/Pieces of Fate/Grookius Zaius.md" data-href="ttrpgs/Pieces of Fate/Grookius Zaius.md" href="ttrpgs/Pieces of Fate/Grookius Zaius.md" class="internal-link" target="_blank" rel="noopener">Grookius Zaius</a></span></td><td><span>Hadozee</span></td><td><ul class="dataview dataview-ul dataview-result-list-ul"><li class="dataview-result-list-li"><span>Sorcerer</span></li></ul></td><td><span>active</span></td><td><span>Drew Barker</span></td></tr><tr><td><span><a data-tooltip-position="top" aria-label="ttrpgs/Pieces of Fate/Hex.md" data-href="ttrpgs/Pieces of Fate/Hex.md" href="ttrpgs/Pieces of Fate/Hex.md" class="internal-link" target="_blank" rel="noopener">Hex</a></span></td><td><span>Imp</span></td><td><span>-</span></td><td><span>-</span></td><td><span>-</span></td></tr><tr><td><span><a data-tooltip-position="top" aria-label="ttrpgs/Pieces of Fate/Jameson Ducky Antidid.md" data-href="ttrpgs/Pieces of Fate/Jameson Ducky Antidid.md" href="ttrpgs/Pieces of Fate/Jameson Ducky Antidid.md" class="internal-link" target="_blank" rel="noopener">Jameson Ducky Antidid</a></span></td><td><span>Giff</span></td><td><ul class="dataview dataview-ul dataview-result-list-ul"><li class="dataview-result-list-li"><span>Artificer</span></li></ul></td><td><span>active</span></td><td><span>Aaron Johnson</span></td></tr></tbody></table>

```dataview
table
	species as "Species",
	class as "Class",
	status as "Status",
	player as "Player"
from "ttrpgs/Pieces of Fate"
where containsword(type,"PC")
sort file.name asc
```
## <br>
-----
-----


## Sessions

```button
name Add Session
type note(ttrpgs/Pieces of Fate/<% tp.user.getThisGameNum(tp) %>_<% tp.date.now("YYYYMMDD") %>, split) template
action session-player
templater true
```
^button-NewSession

```dataview
table summary as "Summary" from "ttrpgs/Pieces of Fate"
where econtains(type,"session")
SORT sessionNum DESC
limit 5
```
###### All Sessions

```dataview
table summary as "Summary" from "ttrpgs/Pieces of Fate"
where econtains(type,"session")
SORT sessionNum desc
```

## <br>
---
---

## Truths
```dataview
task from "ttrpgs/Pieces of Fate"
```
## <br>
---
---

## Locations

```dataview
table choice(containsword(type,"planet"),"Planet","Floating City") as "Type", description as "Description"
from "ttrpgs/Pieces of Fate"
where containsword(type,"planet") OR containsword(type,"city")
where econtains(location,"space")
sort asc
```
## <br>
---
---


## Spelljammers

```dataview
table description as "Description"
where containsword(type,"ship")
sort asc
```
## <br>
---
---


## Pantheon

```dataview
table description as "Description"
where containsword(type,"NPC.deity")
sort asc
```
## <br>
---
---

###### Frontmatter Values
- type:
	- PC
	- PC.familiar
	- NPC
	- NPC.diety
	- location.planet
	- location.city
	- location.star
	- location.establishment.shop
	- location.establishment.tavern
	- location.establishment.inn
	- location.establishment.theatre
	- ship
	- item.mundane
	- item.magic
	- faction
- faction: 
	- North's Crew
	- Cult of Khot
	- House Theodellus
	- Underbarron
	- The Jugglers
	- Ozamata's Crew
	- The Unknowable Ones
	- Sandyfoot
- location: 
	- Illis
	- Orphea
	- Port Royal
	- The Rock of Bral
	- Yazir
	- space.wildspace
	- space.astralsea
- world: 
	- Pieces of Fate
- campaign:
	- Pieces of Fate
- date: 
	- date of note creation
- description:
	- Once sentence description
- gender:
	- male
	- female
	- none
- attunement
	- true
	- false
- rarity
	- common
	- uncommon
	- rare
	- very rare
	- legendary
	- artifact
- tags
	- communication
- requires
	- free hand
- source
	- Sam's Spelljammer
	- D&D SRD

---
---

