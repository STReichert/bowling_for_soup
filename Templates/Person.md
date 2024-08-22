---
type: 
faction: 
location: 
race: 
pronouns: 
class(es): 
title(s): 
tags: 
aliases: 
skills: 
dg-publish:
---

| Faction         | Location         | Race         | Pronouns         | Class(es)            | Title               |
| --------------- | ---------------- | ------------ | ---------------- | -------------------- | ------------------- |
| `=this.faction` | `=this.location` | `=this.race` | `=this.pronouns` | `=this["class(es)"]` | `=this["title(s)"]` |
## Description

## Seen
```dataview
LIST
FROM "🗓️ Sessions"
WHERE contains(file.outlinks, this.file.link)
```
