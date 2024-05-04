---
Origin: "[[After Dark 136]]"
Person: "[[Vaush]]"
tags:
  - Soundbite
---
> *"TAKOMA WEPT"*

Timestamp: [2:25:48](https://youtu.be/H61pA1ZPTs8?t=8748)
# ADDITIONAL INFO

## Episodes
``` dataview
TABLE
FROM "Episodes"
WHERE 
contains(Topics.file.path, this.file.path) 
OR 
contains(file.outlinks.file.path, this.file.path)
OR
contains(file.inlinks.file.path, this.filep)
GROUP BY file.link
```