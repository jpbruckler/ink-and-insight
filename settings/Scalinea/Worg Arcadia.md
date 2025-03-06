---
title: Worg Arcadia
type: location
campaign: sumonho
setting: Scalinea
created: 2022-07-24 09:31:35
location:
  name: Worg Arcadia
  locationtype: Merchant
  region: Aimesland
  settlement: Thornburg
tags:
  - ttrpg/setting/scalinea/location/region/aimesland
  - ttrpg/campaign/sumon-ho
  - ttrpg/setting/scalinea/location/merchant
updated: 2023-11-21T01:32
---
# Worg Arcadia

Campaign:: [[Sumon-Ho]]
Setting:: [[scalinea]]
GovernmentType::
NotableNPCs::

## Description

1 tower exists in the [[Confederation of Independent City-States|CIC]] (main tower)
1 tower is in [[Thornburg]] (secondary tower)

## People in Worg Arcadia

```dataview
TABLE type AS "Person Type", factions AS Factions FROM #ttrpg 
WHERE LastLocation = [[Worg Arcadia]]
  and person.status = "alive"
SORT file.name asc
```
