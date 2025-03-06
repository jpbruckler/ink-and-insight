---
title: Exotic Object
type: location
campaign: sumonho
setting: Scalinea
created: 2022-07-24 08:24:36
location:
  name: Exotic Object
  locationtype: Merchant
  region: Aimesland
  settlement: Aimesville
tags:
  - ttrpg/setting/scalinea/location/region/aimesland
  - ttrpg/campaign/sumon-ho
  - ttrpg/setting/scalinea/location/merchant
updated: 2023-11-21T01:32
---
# Exotic Object

Campaign:: [[Sumon-Ho]]
Setting:: [[scalinea]]
GovernmentType::
NotableNPCs::[[Booster]]

## Description

A magical merchant specializing in uncommon used items.

## People in Exotic Object

```dataview
TABLE type AS "Person Type", factions AS Factions FROM #ttrpg 
WHERE LastLocation = [[Exotic Object]]
  and person.status = "alive"
SORT file.name asc
```
