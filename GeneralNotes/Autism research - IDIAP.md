---
dg-publish: true
---

[AI4Autism - Idiap Publications](https://publications.idiap.ch/projects/show/128)

```dataview 
TABLE
title, 
published,
journal,
Paper_type,
DOI
FROM "Literature_review"
WHERE contains(authors, "Odobez")
SORT published desc 
```