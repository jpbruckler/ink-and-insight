---
title: Battle Mage Assembly
type: location
campaign: sumonho
setting: Scalinea
created: 2022-07-24 07:34:46
location:
  name: Battle Mage Assembly
  locationtype: School
  region: Aimesland
  settlement: Thornburg
tags:
  - ttrpg/setting/scalinea/location/region/aimesland
  - ttrpg/campaign/sumon-ho
  - ttrpg/setting/scalinea/location/school
updated: 2023-11-21T01:32
---
# Battle Mage Assembly

Campaign:: [[Sumon-Ho]]
Setting:: [[scalinea]]
GovernmentType::
NotableNPCs:: [[Jasper Martin]], [[Olgann]]

## Description



## People in Battle Mage Assembly

```dataview
TABLE type AS "Person Type", factions AS Factions FROM #ttrpg 
WHERE LastLocation = [[Battle Mage Assembly]]
  and person.status = "alive"
SORT file.name asc
```
