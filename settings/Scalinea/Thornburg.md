---
title: Thornburg
type: location
campaign: sumonho
setting: Scalinea
created: 2022-07-24 09:23:50
location:
  name: Thornburg
  locationtype: Settlement
  region: Aimesland
  settlement: 
tags:
  - ttrpg/setting/scalinea/location/region/aimesland
  - ttrpg/campaign/sumon-ho
  - ttrpg/setting/scalinea/location/settlement
updated: 2023-11-21T01:32
---
# Thornburg

Campaign:: [[Sumon-Ho]]
Setting:: [[scalinea]]
GovernmentType::
NotableNPCs:: [[Silvia Volgo]]

## Description



## Locations in Thornburg
```dataview
TABLE location.locationtype AS Type from #ttrpg/setting/scalinea/location
WHERE location.settlement = "Thornburg"
```

## People in Thornburg

```dataview
TABLE type AS "Person Type", factions AS Factions FROM #ttrpg 
WHERE LastLocation = [[Thornburg]]
  and person.status = "alive"
SORT file.name asc
```
