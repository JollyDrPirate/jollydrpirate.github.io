---
type: location.planet
faction: 
location: space.wildspace
world: Pieces of Fate
campaign: Pieces of Fate
date: 2022-12-27
description: "trade hub planet"
species: 
gender: 
class: 
aliases: Calipso 1L15
---
[[000 World Index|home]]
# [[Illis]]

## Information
- Main trade hub for this side of the system
- Legends say that civilization began here when a merchant was marooned on an island on the planet.  He made the island his home, and eventually he expanded to cover the whole planet

---
---

## Establishments

```dataview
table description as "Description"
where econtains(type,"location")
where econtains(location,"Illis")
sort asc
```

---
---

## People and Factions

```dataview
table type as "Type", description as "Description"
where econtains(type,"NPC") OR econtains(type,"faction")
where econtains(location,"Illis")
sort type asc
sort asc
```

---
---

## Referenced in Sessions:
```dataview
table campaign as "Campaign", summary as "Summary"
from [[Illis]]
where econtains(type,"session")
sort campaign asc
sort asc
```
