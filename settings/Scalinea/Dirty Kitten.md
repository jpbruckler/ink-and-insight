---
title: Dirty Kitten
type: location
campaign: sumonho
setting: Scalinea
created: 2022-07-24 08:08:20
location:
  name: Dirty Kitten
  locationtype: Tavern
  region: Aimesland
  settlement: Aimesville
tags:
  - ttrpg/setting/scalinea/location/region/aimesland
  - ttrpg/campaign/sumon-ho
  - ttrpg/setting/scalinea/location/tavern
updated: 2023-11-21T01:32
---
# Dirty Kitten

Campaign:: [[Sumon-Ho]]
Setting:: [[scalinea]]
GovernmentType::
NotableNPCs::
Tags: [[The Equilibrium Brotherhood]], [[Brotherhood ID Card]]
## Description

Described by [[Laidor]] as a tavern and shop who's primary product is something called "frozen eggs" which are magic devices used for keeping things cold by absorbing heat.

## People in Dirty Kitten

```dataview
TABLE type AS "Person Type", factions AS Factions FROM #ttrpg 
WHERE LastLocation = [[Dirty Kitten]]
  and person.status = "alive"
SORT file.name asc
```
