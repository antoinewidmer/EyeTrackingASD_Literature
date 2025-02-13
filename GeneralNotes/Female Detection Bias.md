---
dg-publish: true
---

```dataview 
TABLE file.name AS "Note", 
title, 
Paper_type
FROM "Literature_review"
WHERE contains(tags, "Female")
SORT published desc 
```