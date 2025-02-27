---
Institute: UCS Institute for Creative Technologies
Location: southern california
LeadResearcher: Albert “Skip” Rizzo
KeyFocus: 
Website: https://ict.usc.edu/research/labs-groups/medical-virtual-reality/
dg-publish: true
researchgroup:
  - UCSRizzo
AutorToCheck: Rizzo
---

## Publications

```dataview 
TABLE 
title, 
published,
journal,
Paper_type,
DOI
FROM "Literature_review"
WHERE contains(authors, "Rizzo")
SORT published desc 
```



### Applications

```dataview 
TABLE 
title
FROM "AutismResearch/ExistingApp"
WHERE contains(researchgroup, "UCSRizzo")
SORT published desc 
```
