---
title: 🗺️ Nuthornville
created: 2024-10-20T11:33:28Z
aliases:
  - Nuthornberg
  - Nuthornburg
type: settlement
location:
  - "[[🗺️ Aimesland]]"
demonym: 
government: 
ruler: 
founded: 
economy: 
imports: 
exports: 
currency: 
religion: 
deities: 
languages: 
settings: 
tags:
  - ttrpg/campaign/sumon-ho
  - ttrpg/setting/scalinea/location/town
---

# [[🗺️ Nuthornville]]

> [!infobox|float-right]
>
> ## 🗺️ Nuthornville
>
> -- add cover image --
>
> ###### Notable NPCs
> - [[The Mace]]
> - [[Michael Winters|Captain Winters]]
> - [[Lyriena]]
## Description

-   North of the [[🗺️ The Great Forest]]
-   Built as people were moving into the town.
-   Only 40-50 years old.
-   There's some level of socio-economic separation, but the city itself was built to be highly integrated.
-   Governed by a council of 40 people.
   	-   20 of them are elected by the people
   	-   20 are appointed by the city guilds
-   The council appoints a Steward (currently [[Mark Blents]])
   	-   The mayor keeps an advisory panel, called "The Advisory"

## Locations in Nuthornville

```dataview
TABLE type
FROM #ttrpg/setting/scalinea/location 
WHERE contains(location, [[🗺️ Nuthornville]])
```

## People in Nuthornville

```dataview
TABLE WITHOUT ID file.link AS Name,factions
FROM #ttrpg/setting/scalinea/npc
WHERE lastlocation = [[🗺️ Nuthornville]]
SORT file.link
```
