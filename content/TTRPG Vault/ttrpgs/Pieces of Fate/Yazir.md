---
type: location.planet
faction: 
location: space.wildspace
world: Pieces of Fate
campaign: Pieces of Fate
date: 2022-12-27
description: "the now destroyed ancestral homeworld of the Hadozee"
species: 
gender: 
class: 
aliases:
---
[[000 World Index|home]]
# [[Yazir]]

## Information
- destroyed generations ago when it's sun, Cantar, exploded
- ancestral homeworld of the Hadozee


---
---

## Establishments

```dataview
table description as "Description"
where econtains(type,"location")
where econtains(location,"Yazir")
sort asc
```

---
---

## People and Factions

```dataview
table type as "Type", description as "Description"
where econtains(type,"NPC") OR econtains(type,"faction")
where econtains(location,"Yazir")
sort type asc
sort asc
```

---
---

## Referenced in Sessions:
```dataview
table campaign as "Campaign", summary as "Summary"
from [[Yazir]]
where econtains(type,"session")
sort campaign asc
sort asc
```