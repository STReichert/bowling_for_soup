---
type: Place
faction: 
location: 
tags:
  - City
aliases: 
dg-publish: true
---
## Description
A small fishing village far north on the way to Islecross. Aust, O, and Ulfgar have all been through here and have some contacts here. Faem joined the party here.
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
