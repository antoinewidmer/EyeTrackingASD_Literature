---
dg-publish: true
---



```dataview 
TABLE file.name AS "Note", 
EyeMetrics AS "EyeMetrics",
title, 
Paper_type,
device.Type as EyeTracking,
device.sampling_rate as rate
FROM "Literature_review"
WHERE contains(tags, "ASD")
SORT published desc 
```