---
title: Khandrukar
type: location
campaign: sumonho
setting: Scalinea
created: 2022-07-24 08:48:55
location:
  name: Khandrukar
  locationtype: Dungeon
  region: Northern Frontier
  settlement: 
tags:
  - ttrpg/setting/scalinea/location/region/northern-frontier
  - ttrpg/campaign/sumon-ho
  - ttrpg/setting/scalinea/location/dungeon/khandrukar
updated: 2023-11-21T01:32
---
# Khandrukar

Campaign:: [[Sumon-Ho]]
Setting:: [[scalinea]]
GovernmentType::
NotableNPCs::

## Description

We have recently learned that the Khandrukar is in a formation called the [[Stone Tooth]] northwest of [[Blessingburg]]. This is where you will start your quest. We can let you use a ‘[[Divining Dagger]]’ attuned to the [[Necomancers Bane]] that will help you know when you get close. Master smith [[Durgeddin]] was lost at Khandrukar centuries ago, even before the [[Northern Invasion]]. But it’s said that many of his creations are still hidden within Khandrukar; and the [[SLD]] is confident that the [[Necomancers Bane]] is still held within the secret stronghold’s bosom.

## People in Khandrukar

```dataview
TABLE type AS "Person Type", factions AS Factions FROM #ttrpg 
WHERE LastLocation = [[Khandrukar]]
  and person.status = "alive"
SORT file.name asc
```
