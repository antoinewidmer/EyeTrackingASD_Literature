---
Institute: Marcus Autism Centre
Location: Atlanta
LeadResearcher: Ami Klin
KeyFocus: 
Website: https://www.marcus.org/
dg-publish: true
researchgroup:
  - marcus
---

[Warren Jones | Faculty | People | Pediatric Research in Atlanta](https://pedsresearch.org/people/faculty/warren-jones)

[Research | Emory School of Medicine](https://med.emory.edu/departments/pediatrics/divisions/autism/research/index.html)

[Ami Klin, PhD | Marcus Autism Center](https://www.marcus.org/about-marcus-autism-center/meet-our-leadership/ami-klin)

## publications

```dataview 
TABLE 
title, 
published,
journal,
Paper_type,
DOI
FROM "Literature_review"
WHERE contains(researchgroup, "marcus")
SORT published desc 
```


## Applications

```dataview 
TABLE 
title
FROM "AutismResearch/ExistingApp"
WHERE contains(researchgroup, "marcus")
SORT published desc 
```