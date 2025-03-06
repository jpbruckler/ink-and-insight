---
title: Aimesville
uuid: 7bf4aa35-f96f-45cd-a134-48eafed551a9
type: ttrpg-location
created: 2023-07-27
updated: 2023-07-27
tpl-version: 1
campaign: 
setting: "[[scalinea]]"
locationtype: Settlement
region: "[[50 TTRPG/51 Settings/Scalinea/Aimesland]]"
settlement: 
population: 
theme: 
terrain: 
founder: 
leaders: 
rulers: 
religions: 
defenses: 
imports: 
exports: 
aliases: []
tags:
  - ttrpg
  - ttrpg/setting/scalinea
---
# `=this.file.name`

> [!abstract|float-right-small]
> ![[PlaceholderImage.png|200px]]
>
> ###### Info
>
> | | |
> | --- | --- |
> | **Alias** | `=this.aliases` |
> | **Type** | `=this.type` |
> | **Population** | `=this.population` |
> | **Theme** | `=this.theme` |
> | **Region** | `=link(this.region)` |
> | **Terrain** | `=this.terrain` |
>
> ###### Travel
>
> | | |
> | --- | --- |
> | Method | `=[[Transportation]].method[[[The Party]].transportation].name` |
>
> ###### Politics
>
> | | |
> | ---|---|
> | **Founder** | `=this.founder` |
> | **Ruler(s)** | `=this.Rulers` |
> | **Leaders** | `=this.Leaders` |
> | **Govt Type** | `=this.GovtType` |
> | **Defenses** | `=this.defenses` |
> | **Religion(s)** | `=link(this.religions)` |
>
> ###### Commerce
>
> | | |
> | ---|---|
> | **Imports** | `=this.imports` |
> | **Exports** | `=this.exports` |

> [!map]+
>
> ```leaflet
> uuid: Aimesland
> image: [[PlaceholderImage.png]]
> ```

## Locations in `=this.file.name`

```dataview
TABLE 
    locationtype AS Type,
    settlement AS Settlement,
    region AS Region
FROM #ttrpg
WHERE contains(file.outlinks, [[Aimesville]])
```

