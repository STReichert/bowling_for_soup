---
type: NPC
faction: 
location:
  - "[[Brawny Awl]]"
race: Elf
pronouns: he/him
class(es): 
title(s): 
tags: 
aliases: 
skills: 
dg-publish: true
---

| Faction         | Location         | Race         | Pronouns         | Class(es)            | Title               |
| --------------- | ---------------- | ------------ | ---------------- | -------------------- | ------------------- |
| `=this.faction` | `=this.location` | `=this.race` | `=this.pronouns` | `=this["class(es)"]` | `=this["title(s)"]` |
## Description
The head barkeep at the tavern in the Brawny Awl. Chill dude.
## Seen
```dataview
LIST
FROM "🗓️ Sessions"
WHERE contains(file.outlinks, this.file.link)
```
