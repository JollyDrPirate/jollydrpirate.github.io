---
type: location.city
faction: 
location: space.wildspace
world: Pieces of Fate
campaign: Pieces of Fate
date: 2022-12-27
description: "a city, situated on an asteroid orbiting Toril"
species: 
gender: 
class: 
aliases: Bral
---
[[ttrpgs/Pieces of Fate/000 World Index|home]]
# [[The Rock of Bral]]

## Information
- childhood home of [[Jameson Ducky Antidid]]


---
---

## Establishments

```dataview
table description as "Description"
where econtains(type,"location")
where econtains(location,"The Rock of Bral")
sort asc
```

---
---

## People and Factions

```dataview
table type as "Type", description as "Description"
where econtains(type,"NPC") OR econtains(type,"faction")
where econtains(location,"The Rock of Bral")
sort type asc
sort asc
```

---
---

## Referenced in Sessions:

```dataview
table campaign as "Campaign"
from [[The Rock of Bral]]
where econtains(type,"session")
sort campaign asc
sort asc
```