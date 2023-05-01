---
type: location.planet
faction: 
location: space.wildspace
world: Pieces of Fate
campaign: Pieces of Fate
date: 2022-12-27
description: "planet in the astral sea, closest neighbor of Orphea"
species: 
gender: 
class: 
aliases:
---
[[000 World Index|home]]
# [[Nee A'bohr]]

## Information
- Located in its own wildspace system
- It is a wild planet, covered in dense green foliage
- No sapient population or civilization calls the planet home
- teleportation circles exist linking Nee A'bor and [[Orphea]]
	- these circles are used by the [[Cult of Khot]]


---
---

## Establishments

```dataview
table description as "Description"
where econtains(type,"location")
where econtains(location,"Nee A'bohr")
sort asc
```

---
---

## People and Factions

```dataview
table type as "Type", description as "Description"
where econtains(type,"NPC") OR econtains(type,"faction")
where econtains(location,"Nee A'bohr")
sort type asc
sort asc
```

---
---
## Referenced in Sessions:
```dataview
table campaign as "Campaign", summary as "Summary"
from [[Nee A'bohr]]
where econtains(type,"session")
sort campaign asc
sort asc
```