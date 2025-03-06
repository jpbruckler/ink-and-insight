---
title: Stone Tooth
type: location
campaign: sumonho
setting: Scalinea
created: 2022-07-24 07:42:59
location:
  name: Stone Tooth
  locationtype: Mountain
  region: Aimesland
  settlement: 
tags:
  - ttrpg/setting/scalinea/location/region/aimesland
  - ttrpg/campaign/sumon-ho
  - ttrpg/setting/scalinea/location/mountain
updated: 2023-11-21T01:32
---
# Stone Tooth

Campaign:: [[Sumon-Ho]]
Setting:: [[scalinea]]
GovernmentType::
NotableNPCs::

## Description

A rocky formation northwest of [[Blessingburg]]. [[Khandrukar]] is located here.

## People in Stone Tooth

```dataview
TABLE type AS "Person Type", factions AS Factions FROM #ttrpg 
WHERE LastLocation = [[Stone Tooth]]
  and person.status = "alive"
SORT file.name asc
```
