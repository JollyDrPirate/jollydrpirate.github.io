---
type: location.city
faction: 
location: space.wildspace
world: Pieces of Fate
campaign: Pieces of Fate
date: 2022-12-27
description: "The spaceport home of Spelljammer Academy"
species: 
gender: 
class: 
aliases:
---
[[000 World Index|home]]
# [[Port Royal]]

## Information


---
---

## Establishments

```dataview
table description as "Description"
where econtains(type,"location")
where econtains(location,"Port Royal")
sort asc
```

---
---

## People and Factions

```dataview
table type as "Type", description as "Description"
where econtains(type,"NPC") OR econtains(type,"faction")
where econtains(location,"Port Royal")
sort type asc
sort asc
```

---
---
## Referenced in Sessions:
```dataview
table campaign as "Campaign", summary as "Summary"
from [[Port Royal]]
where econtains(type,"session")
sort campaign asc
sort asc
```