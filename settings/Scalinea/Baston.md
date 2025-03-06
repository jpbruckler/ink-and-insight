---
title: Baston
type: location
campaign: sumonho
setting: Scalinea
created: 2022-07-24 07:33:10
location:
  name: Baston
  locationtype: World
  region: 
  settlement: 
tags:
  - ttrpg/campaign/sumon-ho
  - ttrpg/setting/scalinea/location/world
updated: 2023-11-21T01:32
---
# Baston

Campaign:: [[Sumon-Ho]]
Setting:: [[scalinea]]
GovernmentType::
NotableNPCs::

## Description

The world that the setting of [[scalinea]] concerns iteslf with.

## People in Baston

```dataview
TABLE type AS "Person Type", factions AS Factions FROM #ttrpg 
WHERE LastLocation = [[Baston]]
  and person.status = "alive"
SORT file.name asc
```
