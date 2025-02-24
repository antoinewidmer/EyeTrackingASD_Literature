---
researchgroup:
  - duke
relatedApp: SenseToKnow
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