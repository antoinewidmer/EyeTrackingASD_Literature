---
dg-publish: true
---


[Publications - Département de psychiatrie - UNIGE](https://www.unige.ch/medecine/psyat/groupes-de-recherche/1033schaer/publications)

```dataview 
TABLE 
title, 
published,
journal,
Paper_type,
DOI
FROM "Literature_review"
WHERE contains(authors, "Schaer")
SORT published desc 
```