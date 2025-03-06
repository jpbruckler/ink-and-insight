---
title: Honorville
type: location
campaign: sumonho
setting: Scalinea
created: 2022-07-24 08:44:01
location:
  name: Honorville
  locationtype: Settlement
  region: Aimesland
  settlement: 
tags:
  - ttrpg/setting/scalinea/location/region/aimesland
  - ttrpg/campaign/sumon-ho
  - ttrpg/setting/scalinea/location/settlement
updated: 2023-11-21T01:32
---
# Honorville

Campaign:: [[Sumon-Ho]]
Setting:: [[scalinea]]
GovernmentType::
NotableNPCs::

## Description



## Locations in Honorville
```dataview
TABLE location.locationtype AS Type from #ttrpg/setting/scalinea/location
WHERE location.settlement = "Honorville"
```

## People in Honorville

```dataview
TABLE type AS "Person Type", factions AS Factions FROM #ttrpg 
WHERE LastLocation = [[Honorville]]
  and person.status = "alive"
SORT file.name asc
```
