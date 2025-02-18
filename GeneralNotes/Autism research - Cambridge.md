

```dataview 
TABLE
title, 
published,
journal,
Paper_type,
DOI
FROM "Literature_review"
WHERE contains(researchgroup, "cambridge")
SORT published desc 
```