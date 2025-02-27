---
company: 
researchgroup:
  - UCSD
relatedApp:
  - GeoPref
keyAspect: 
dg-publish: true
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