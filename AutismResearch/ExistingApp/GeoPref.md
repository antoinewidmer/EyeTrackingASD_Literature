---
researchgroup:
  - UCSD
relatedApp:
  - GeoPref
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