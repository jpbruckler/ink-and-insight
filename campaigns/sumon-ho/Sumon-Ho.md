---
title: "Sumon-Ho"
created: 2024-10-20T11:33:28Z
aliases: []
setting: "[[Scalinea]]"
tags:
  - ttrpg/campaign/index
---

First session: January 30, 2020

## Quick Links


- [New Session](obsidian://advanced-uri?vault=technosage-chronicles&filepath=50%20TTRPG%2F52%20Campaigns%2FSumon-Ho%2Fsessions%2fUntitled.md)


## Characters

```dataview
TABLE WITHOUT ID
    file.link AS Character,
    player AS Player,
    status AS Status
FROM #ttrpg/campaign/sumon-ho/pc
```

## Top NPCs

```dataview
table without id
    file.link as "NPC", length(file.inlinks) as "Mentions"
from #ttrpg/scalinea/npc
sort length(file.inlinks) desc
limit 5
```

