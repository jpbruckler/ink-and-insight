---
title: The Great Forest
created: 2024-10-20T11:33:28Z
aliases: 
type: forest
location:
  - "[[🗺️ Aimesland]]"
demonym: 
government: 
ruler: "[[Eldrin]]"
founded: 
economy: 
imports: 
exports: 
currency: 
religion: 
deities: 
languages: 
settings:
  - "[[Scalinea]]"
tags:
  - ttrpg/setting/scalinea/location
  - ttrpg/location
---

# [[The Great Forest]]

> [!infobox|float-right]
>
> ## The Great Forest
>
> -- add cover image --
>
> ###### Notable NPCs
> - [[Eldrin|Master Druid]]

## Locations in The Great Forest

```dataview
TABLE type
FROM #ttrpg/setting/scalinea/location
WHERE contains(location, [[🗺️ The Great Forest]])
```

## People in The Great Forest

```dataview
TABLE WITHOUT ID file.link AS Name,factions
FROM #ttrpg/setting/scalinea/npc
WHERE lastlocation = [[🗺️ The Great Forest]]
SORT file.link
```
