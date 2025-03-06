---
title: Erika
campaign: Sumon-Ho
setting: Scalinea
created: 2024-10-20T03:07:27Z
aliases: 
status: 
species: Human
factions:
  - "[[SLD]]"
tags:
  - ttrpg/setting/scalinea/npc
  - ttrpg/npc
---

>[!info|float-right-small] Details
> ![[ttrpg-erika.png|250px]]
> ---
> 
> ##### At a glance
> 
> - Status: `$= dv.current().status || "unknown"`
> - Species: `$= dv.current().species || "unknown"`
> - Factions: `$= dv.current().factions || "unknown"`
> - First appeared:
> 
## Description

Member of [[Averos]]' security detail.

##### Motivation/Goals:


###### Personality:  


###### Appearance:  

Athletic (similar to [[Kereshi Khill]] in health and power)

## Known Associates

- [[Averos]]
- [[Olseris]]
- [[Eric]]
- [[Ereak]]
- [[Ralph]]
- [[Aaronnor]]
- [[Eldora]]

## Recent Sessions

```dataview
table without id
    file.link as "Session", campaign, created
from #ttrpg/session/sumon-ho
where contains(file.outlinks, [[]])
sort date desc
limit 10
```