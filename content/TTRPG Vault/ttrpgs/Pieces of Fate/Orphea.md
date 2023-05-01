---
type: location.city
faction: 
location: space.wildspace
world: Pieces of Fate
campaign: Pieces of Fate
date: 2022-12-27
description: "a free floating city in the Astral Sea"
species: 
gender: 
class: 
aliases:
---
[[000 World Index|home]]
# [[Orphea]]

## Information
- a free floating city in the Astral Sea
- founded and inhabited by Astral Elves
- childhood home of [[Alistair Theodellus II]]

---
---

## Establishments

```dataview
table description as "Description"
where econtains(type,"location")
where econtains(location,"Orphea")
sort asc
```

---
---

## People and Factions

```dataview
table type as "Type", description as "Description"
where econtains(type,"NPC") or econtains(type,"faction")
where econtains(location,"Orphea")
sort type asc
sort asc
```

---
---

## Referenced in Sessions:
```dataview
table campaign as "Campaign", summary as "Summary"
from [[Orphea]]
where econtains(type,"session")
sort campaign asc
sort asc
```

