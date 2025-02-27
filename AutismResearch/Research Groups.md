---
dg-publish: true
---
```dataview 
TABLE
Institute, 
Location, 
LeadResearcher, 
KeyFocus,
Website
FROM "AutismResearch/researchgroups" 
WHERE !startswith(file.name, "00")
```
