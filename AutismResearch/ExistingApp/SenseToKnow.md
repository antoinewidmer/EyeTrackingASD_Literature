---
researchgroup:
  - duke
relatedApp: SenseToKnow
company:
keyAspect:
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