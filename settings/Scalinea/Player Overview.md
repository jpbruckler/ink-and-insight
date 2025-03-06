---
cssclasses:
  - cards
  - cards-1-1
  - cards-cols-4
campaign: "[[Sumon-Ho]]"
setting: "[[scalinea]]"
uuid: db876b2e-66c8-41b0-aac5-6db52264be98
created: 2023-11-09T17:47
updated: 2023-11-21T01:31
---
```dataview
TABLE WITHOUT ID
 link(file.path, name) AS "Name",
 embed(token) AS "Art",
 race AS "Race",
 class AS "Class",
 background AS "Background",
 campaign AS Campaign
FROM "ttrpg/Scalinea/Sumon-Ho"
WHERE contains(type, "ttrpg-pc")
WHERE !contains(type, "backup") AND pcstatus = "💖" AND inparty = true
SORT file.name asc
```
