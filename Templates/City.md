---
type: 
faction: 
location: 
tags: 
aliases: 
dg-publish:
---
## Description

## People and Contacts
```dataview
TABLE WITHOUT ID file.link as Name, faction as Faction, tags
FROM "🙋 People"
WHERE contains(location, this.file.link)
```
## Places We've Been
```dataview
LIST
FROM "🗺️ Places/Businesses & Specifics"
WHERE contains(location, this.file.link)
```
