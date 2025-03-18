---
dg-publish: true
---


## Articles on Eye-Tracking in ASD Detection

```dataview 
TABLE 
EyeMetrics AS "EyeMetrics",
title, 
Paper_type,
device.Type as EyeTracking,
device.sampling_rate as rate
FROM "Literature_review"
WHERE contains(tags, "EyeTracking")
SORT published desc 
```


## Articles on Micro-Expression in ASD Detection

```dataview 
TABLE 
title,
Paper_type
FROM "Literature_review"
WHERE contains(tags, "Micro-Expression")
SORT published desc 
```