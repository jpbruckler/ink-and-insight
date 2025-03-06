---
title: Tun Tavern
type: location
campaign: sumonho
setting: Scalinea
created: 2022-07-24 09:28:02
location:
  name: Tun Tavern
  locationtype: Tavern
  region: Aimesland
  settlement: Thornburg
tags:
  - ttrpg/setting/scalinea/location/region/aimesland
  - ttrpg/campaign/sumon-ho
  - ttrpg/setting/scalinea/location/tavern
updated: 2023-11-21T01:32
---
# Tun Tavern

Campaign:: [[Sumon-Ho]]
Setting:: [[scalinea]]
GovernmentType::
NotableNPCs::

## Description



## People in Tun Tavern

```dataview
TABLE type AS "Person Type", factions AS Factions FROM #ttrpg 
WHERE LastLocation = [[Tun Tavern]]
  and person.status = "alive"
SORT file.name asc
```
