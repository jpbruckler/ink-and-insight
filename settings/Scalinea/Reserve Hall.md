---
title: Reserve Hall
type: location
campaign: sumonho
setting: Scalinea
created: 2022-07-24 09:16:21
location:
  name: Reserve Hall
  locationtype: Other
  region: Ravaged Lands
  settlement: 
tags:
  - ttrpg/setting/scalinea/location/region/ravaged-lands
  - ttrpg/campaign/sumon-ho
  - ttrpg/setting/scalinea/location/other
updated: 2023-11-21T01:32
---
# Reserve Hall

Campaign:: [[Sumon-Ho]]
Setting:: [[scalinea]]
GovernmentType::
NotableNPCs::

## Description

- [[Nabrim the Terrific|Nabrim]] the Terrific didn’t have an idea for them to escape the basement without going through the above ground portion of the watch tower. The river through the Reserve Hall had a barrier farther down so that way would not work.


## People in Reserve Hall

```dataview
TABLE type AS "Person Type", factions AS Factions FROM #ttrpg 
WHERE LastLocation = [[Reserve Hall]]
  and person.status = "alive"
SORT file.name asc
```
