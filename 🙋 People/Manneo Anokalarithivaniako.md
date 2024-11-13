---
type: 
faction: 
location:
  - "[[Uthodurn]]"
race: Goliath
pronouns: he/him
class(es): 
title(s): 
tags: 
aliases:
  - TongueTeacher
skills: 
dg-publish: true
---

| Faction         | Location         | Race         | Pronouns         | Class(es)            | Title               |
| --------------- | ---------------- | ------------ | ---------------- | -------------------- | ------------------- |
| `=this.faction` | `=this.location` | `=this.race` | `=this.pronouns` | `=this["class(es)"]` | `=this["title(s)"]` |
## Description
Tall muscular goliath academic teaching Giant to students in Uthodurn. Super O's type of friend.
## Seen
```dataview
LIST
FROM "🗓️ Sessions"
WHERE contains(file.outlinks, this.file.link)
```
