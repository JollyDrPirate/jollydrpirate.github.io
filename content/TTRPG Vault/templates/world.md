<% "---" %>
world: <% tp.user.getThisWorld(tp) %>
setting:
campaign: <% tp.file.folder(false) %>
status: active
role: player
system:
type: world
aliases:
<% "---" %>
# The World of <% tp.file.folder(false) %>

## Player Characters

-

## Sessions

```button
name Add Session
type note(ttrpgs/<% tp.file.folder(false) %>/<% tp.user.createWorldSessionbtn(tp) %>_<% tp.user.getSessionDate(tp) %>, split) template
action session-player
templater true
```
^button-NewSession


```dataview
table summary as "Summary" from "ttrpgs/<% tp.file.folder(false) %>"
where contains(type,"session")
SORT sessionNum ASC
```
