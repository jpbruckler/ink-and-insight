---
title: Fleet Foot Stables
type: location
campaign: sumonho
setting: Scalinea
created: 2022-07-24 08:33:09
location:
  name: Fleet Foot Stables
  locationtype: Other
  region: Aimesland
  settlement: Fowlerville
tags:
  - ttrpg/setting/scalinea/location/region/aimesland
  - ttrpg/campaign/sumon-ho
  - ttrpg/setting/scalinea/location/stables
updated: 2023-11-21T01:32
---
# Fleet Foot Stables

Campaign:: [[Sumon-Ho]]
Setting:: [[scalinea]]
GovernmentType::
NotableNPCs::[[Allison Ramshold]]

## Description

Proprietor: [[Allison Ramshold]]

## Notes

- Caught fire in [[001-20200130]] during the Orc attack.
	- [[Danger Inc.]] helped a bucket brigade put out the fire with the help of a cleric of [[Rauni]]

## People in Fleet Foot Stables

```dataview
TABLE type AS "Person Type", factions AS Factions FROM #ttrpg 
WHERE LastLocation = [[Fleet Foot Stables]]
  and person.status = "alive"
SORT file.name asc
```
