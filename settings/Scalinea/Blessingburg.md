---
title: Blessingburg
type: location
campaign: sumonho
setting: Scalinea
created: 2022-07-24 07:35:56
location:
  name: Blessingburg
  locationtype: Settlement
  region: Aimesland
  settlement: 
tags:
  - ttrpg/setting/scalinea/location/region/aimesland
  - ttrpg/campaign/sumon-ho
  - ttrpg/setting/scalinea/location/settlement
updated: 2023-11-21T01:32
---
# Blessingburg

Campaign:: [[Sumon-Ho]]
Setting:: [[scalinea]]
GovernmentType::
NotableNPCs::

![[blessingburg.png]]

## Description

Located 1/2 a days' travel from both the [[Barrier Mountains|Great Divide]] and the [[🗺️ Dancing Drakes Inn]], Blessingburg is a small town/fort, serving as the last stop for provisions before entering the [[Barrier Mountains]] through the [[Phelandor Pass]].

## Locations in Blessingburg
```dataview
TABLE location.locationtype AS Type from #ttrpg/setting/scalinea/location/region/
WHERE location.settlement = "Blessingburg"
```

## People in Blessingburg

```dataview
TABLE type AS "Person Type", factions AS Factions FROM #ttrpg 
WHERE LastLocation = [[Blessingburg]]
  and person.status = "alive"
SORT file.name asc
```
