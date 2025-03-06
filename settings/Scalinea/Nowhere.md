---
title: Nowhere
type: location
campaign: sumonho
setting: Scalinea
created: 2022-07-24 09:05:08
location:
  name: Nowhere
  locationtype: Demiplane
  region: 
  settlement: 
tags:
  - ttrpg/campaign/sumon-ho
  - ttrpg/setting/scalinea/location/demiplane
updated: 2023-11-21T01:32
---
# Nowhere

Campaign:: [[Sumon-Ho]]
Setting:: [[scalinea]]
GovernmentType::
NotableNPCs::

## Description

- Rumored to house the remains of the [[Eternal One]]

## People in Nowhere

```dataview
TABLE type AS "Person Type", factions AS Factions FROM #ttrpg 
WHERE LastLocation = [[Nowhere]]
  and person.status = "alive"
SORT file.name asc
```
