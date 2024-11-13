---
type: NPC
faction: 
location:
  - "[[Brawny Awl]]"
race: Elf
pronouns: he/him
class(es):
  - Ranger
title(s): 
tags:
  - hunter
aliases: 
skills: 
dg-publish: true
---

| Faction         | Location         | Race         | Pronouns         | Class(es)            | Title               |
| --------------- | ---------------- | ------------ | ---------------- | -------------------- | ------------------- |
| `=this.faction` | `=this.location` | `=this.race` | `=this.pronouns` | `=this["class(es)"]` | `=this["title(s)"]` |
## Description
A member of the Brawny Awl community, a bit of an interesting duck. An elf hunter dark skinned (the color of an oak tree). He lives around the Brawny awl. 

Spends most of his time in the woods.
## Seen
```dataview
LIST
FROM "🗓️ Sessions"
WHERE contains(file.outlinks, this.file.link)
```
