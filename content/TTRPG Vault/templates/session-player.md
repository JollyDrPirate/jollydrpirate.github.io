<% "---" %>
type: session
campaign: <% tp.file.folder(false) %>
world: <% tp.user.getThisWorld(tp) %>
sessionNum: <% tp.user.getThisGameNum(tp) %>
location: 
date: <% tp.date.now("YYYY-MM-DD") %>

long_rest: false
short_rest: false
summary: ""
tags: inbox
art: ""
<% "---" %>
[[ttrpgs/<% tp.file.folder(false) %>/000 World Index|home]]
# [[<% tp.file.title %>]]
## Session Summary

 > [!tldr] [[<% tp.file.title %>]]
>  ^summary

---

## Recap

![[<% tp.user.getLastGameTitle(tp) %>#^summary]]


---

## Log

