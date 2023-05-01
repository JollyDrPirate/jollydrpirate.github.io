---
aliases: campaigns
---
# [[TTRPGs Campaign Index]]

## List of current campaigns


```button
name Add New Campaign
type command
action QuickAdd: Template - Add Campaign
```
^button-btnAddNewWorld

```dataviewjs
let totalGames;
function getNumOfGames(campaign) {
	let numOfGames = app.plugins.plugins.dataview.api
        .pages(`"ttrpgs/${campaign}"`)
        .where(page => {
            if (page.type === 'session') {
                if (page.campaign === campaign) {
	                totalGames = totalGames +1;
                    return true;
                }
            }
        }).length
	return numOfGames
}

dv.table(["Campaign","System","Sessions", "Role","Status"],dv.pages('"ttrpgs"')
  .where(b => b.type === "world")
  .sort(b => b.status)
  .map(b => [dv.fileLink(b.file.path,false,[b.campaign]),b.system,getNumOfGames(b.campaign),b.role,b.status]))
```


