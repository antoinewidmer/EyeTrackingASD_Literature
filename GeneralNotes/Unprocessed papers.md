```dataview 
TABLE
title, 
published,
journal,
Paper_type,
DOI
FROM "Literature_review"
WHERE toProcess=True
SORT published desc 
```