---
type: NPC
faction: 
location:
  - "[[Brawny Awl]]"
race: Dwarf
pronouns: she/her
class(es): 
title(s): 
tags: 
aliases: 
skills:
  - Woodcarving
dg-publish: true
---

| Faction         | Location         | Race         | Pronouns         | Class(es)            | Title               |
| --------------- | ---------------- | ------------ | ---------------- | -------------------- | ------------------- |
| `=this.faction` | `=this.location` | `=this.race` | `=this.pronouns` | `=this["class(es)"]` | `=this["title(s)"]` |
## Description
An old dwarf woman who moved to the Brawny Awl whose family maybe stabbed her in the back and was maybe living on the streets of Uthodurn? She makes beautiful wood carvings and picks Herby-derbies from Ulfgar's defunct garden (ssshhhhh, its a secret).
## Seen
```dataview
LIST
FROM "🗓️ Sessions"
WHERE contains(file.outlinks, this.file.link)
```
