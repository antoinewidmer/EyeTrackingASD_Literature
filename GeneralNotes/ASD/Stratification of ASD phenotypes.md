---
dg-publish : true
---

[Publications EU Aims project](https://www.aims-2-trials.eu/news/publications/)


```dataview 
TABLE 
title, 
published,
journal,
Paper_type,
DOI
FROM "Literature_review"
WHERE contains(tags, "stratification")
SORT published desc 
```