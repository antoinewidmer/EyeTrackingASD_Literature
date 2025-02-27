---
company: earlitecdx.com
relatedApp:
  - earlipoint
researchgroup:
  - marcus
keyAspect: early detection of autism
dg-publish: true
---


## publications

```dataview 
TABLE 
title, 
published,
journal,
Paper_type,
DOI
FROM "Literature_review"
WHERE contains(relatedApp, "earlipoint")
SORT published desc 
```

[JAMA Publishes Two Large Studies Demonstrating the Diagnostic Accuracy of EarliTec’s Evaluation for Autism in Children as Young as 16 Months - EarliTec Diagnostics, Inc.](https://earlitecdx.com/2023/09/05/jama-publishes-two-large-studies-demonstrating-the-diagnostic-accuracy-of-earlitecs-evaluation-for-autism-in-children-as-young-as-16-months/)