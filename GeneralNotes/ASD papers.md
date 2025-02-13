---
dg-publish: true
---



```dataview 
TABLE
title, 
Paper_type
FROM "Literature_review"
WHERE contains(tags, "ASD")
SORT published desc 
```