---
dg-publish: true
---



```dataview 
TABLE
title, 
Paper_type
FROM "Literature_review"
WHERE contains(tags, "autism")
SORT published desc 
```