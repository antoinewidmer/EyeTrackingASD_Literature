---
company: 
researchgroup:
  - UCSD
relatedApp:
  - GeoPref
keyAspect:
---



## publications

```dataview 
TABLE 
title, 
published,
researchgroup
FROM "Literature_review"
WHERE contains(relatedApp, "GeoPref")
SORT published desc 
```