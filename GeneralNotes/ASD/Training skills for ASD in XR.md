---
dg-publish: true
---


## Literature reviews

```dataview 
TABLE 
title, 
published,
journal,
Paper_type,
DOI
FROM "Literature_review"
WHERE contains(tags, "literRevTSASDXR")
SORT published desc 
```

## Articles to read

```dataview 
TABLE 
title, 
published,
journal,
Paper_type,
DOI
FROM "Literature_review"
WHERE contains(tags, "TSASDtoread")
SORT published desc 
```