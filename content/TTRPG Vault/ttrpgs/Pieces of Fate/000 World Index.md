---
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

