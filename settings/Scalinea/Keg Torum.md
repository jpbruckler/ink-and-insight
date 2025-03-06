---
title: Keg Torum
type: location
campaign: sumonho
setting: Scalinea
created: 2022-07-24 08:46:21
location:
  name: Keg Torum
  locationtype: Fort
  region: Ravaged Lands
  settlement: 
tags:
  - ttrpg/setting/scalinea/location/region/ravaged-lands
  - ttrpg/campaign/sumon-ho
  - ttrpg/setting/scalinea/location/fort
updated: 2023-11-21T01:32
---
# Keg Torum

Campaign:: [[Sumon-Ho]]
Setting:: [[scalinea]]
GovernmentType::
NotableNPCs::

## Description

- Near [[Strolbren Tower]]

## People in Keg Torum

```dataview
TABLE type AS "Person Type", factions AS Factions FROM #ttrpg 
WHERE LastLocation = [[Keg Torum]]
  and person.status = "alive"
SORT file.name asc
```
