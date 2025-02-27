---
researchgroup:
  - duke
relatedApp:
  - SenseToKnow
company: 
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
WHERE contains(relatedApp, "SenseToKnow")
SORT published desc 
```