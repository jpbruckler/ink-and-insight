---
title: Eljas
uuid: e6190095-e1c7-48ae-b93d-9b5f347a3683
type:
  - ttrpg-pc
tpl-version: 1.3
created: 2023-07-30
updated: 2023-11-21T01:31
campaign: "[[Sumon-Ho]]"
token: "[[eljas.png]]"
race: "[[ttrpg/rulesets/DnD/5e/compendium/Races/Human|Human]]"
class:
  - "[[Paladin]]"
level: "3"
player: "[[@Nick Hyatt]]"
background: 
sheet: 
pronouns: he/him
pcstatus: 💀
statblock:
  abilities: +3, +7, +2, 0, +2, +1
  ac: 18
  speed: 30
  fortitude: 
  will: 
  reflex: 
  perception: 
  senses:
    - ?? passive perception
    - ?? passive investigation
    - ?? passive insight
  languages: Common
inparty: 
---

> [!quote]
> "Aww, dammit."
> — player, probably

> [!note|float-right-small]
> ![[eljas.png|250px]]
>
> ###### Basics
>
> | | |
> | --- | --- |
> | **Ancestry** | `=link(this.race)` |
> | **Status** | `=this.pcstatus` |
> | **Height**  | - |
> | **Weight** | - |
> | **Size** | Medium |
>
> ###### Abilities
>
> | | |
> | --- | :---: |
> | **Class**         | `=link(this.class)` |
> | **AC**            | `=this.statblock.ac` |
> | **Speed**         | `=this.statblock.speed` |
> | **Fortitude**     | `=this.statblock.fortitude` |
> | **Will**          | `=this.statblock.will` |
> | **Reflex**        | `=this.statblock.reflex` |
> | **Strength**      | `=split(this.statblock.abilities, ",")[0]` |
> | **Dexterity**     | `=split(this.statblock.abilities, ",")[1]` |
> | **Constitution**  | `=split(this.statblock.abilities, ",")[2]` |
> | **Intelligence**  | `=split(this.statblock.abilities, ",")[3]` |
> | **Wisdom**        | `=split(this.statblock.abilities, ",")[4]` |
> | **Charisma**      | `=split(this.statblock.abilities, ",")[5]` |
> | **Senses**        | `=this.statblock.senses` |
> | **Languages**     | `=list(this.statblock.languages)` |

## Notes
- Grew up with [[Olseris]]
### Appears in Sessions

```dataview
TABLE without ID
 link(file.path, name) AS "Session",
 summary AS "Summary"
FROM [[]]
WHERE contains(type, "ttrpg-session")
```
