
---
---

## Establishments

```dataview
table description as "Description"
where econtains(type,"location")
where econtains(location,"<% tp.file.title %>")
sort asc
```

---
---

## People and Factions

```dataview
table type as "Type", description as "Description"
where econtains(type,"NPC") OR econtains(type,"faction")
where econtains(location,"<% tp.file.title %>")
sort type asc
sort asc
```

---
---