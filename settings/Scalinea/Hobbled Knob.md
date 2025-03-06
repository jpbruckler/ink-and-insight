---
title: Hobbled Knob
type: location
campaign: sumonho
setting: Scalinea
created: 2022-07-24 08:42:06
location:
  name: Hobbled Knob
  locationtype: Tavern
  region: Aimesland
  settlement: Aimesville
tags:
  - ttrpg/setting/scalinea/location/region/aimesland
  - ttrpg/campaign/sumon-ho
  - ttrpg/setting/scalinea/location/tavern
updated: 2023-11-21T01:32
---
# Hobbled Knob

Campaign:: [[Sumon-Ho]]
Setting:: [[scalinea]]
GovernmentType::
NotableNPCs::
Tags: [[027-20201002]]

## Description

Slummy bar where [[Kereshi Khill|Kereshi]] got in a fight and ran from the cops

## People in Hobbled Knob

```dataview
TABLE type AS "Person Type", factions AS Factions FROM #ttrpg 
WHERE LastLocation = [[Hobbled Knob]]
  and person.status = "alive"
SORT file.name asc
```
