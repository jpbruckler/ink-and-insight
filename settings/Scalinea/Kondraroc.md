---
title: Kondraroc
type: location
campaign: sumonho
setting: Scalinea
created: 2022-07-24 08:50:14
location:
  name: Kondraroc
  locationtype: Settlement
  region: Ravaged Lands
  settlement: 
tags:
  - ttrpg/setting/scalinea/location/region/ravaged-lands
  - ttrpg/campaign/sumon-ho
  - ttrpg/setting/scalinea/location/settlement
updated: 2023-11-21T01:32
---
# Kondraroc

Campaign:: [[Sumon-Ho]]
Setting:: [[scalinea]]
GovernmentType::
NotableNPCs::
Tags: [[052-20210915]]

## Description

Kondraroc is a hobgoblin city, near [[Strolbren Tower]]

## Locations in Kondraroc
```dataview
TABLE location.locationtype AS Type from #ttrpg/setting/scalinea/location
WHERE location.settlement = "Kondraroc"
```

## People in Kondraroc

```dataview
TABLE type AS "Person Type", factions AS Factions FROM #ttrpg 
WHERE LastLocation = [[Kondraroc]]
  and person.status = "alive"
SORT file.name asc
```
