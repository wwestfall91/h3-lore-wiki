---
Origin: "[[H3TV 59]]"
Person: "[[Keemstar]]"
tags:
  - Soundbite
  - "#Vape"
---
> *"Baby I need a - I need a JUUL POD!"*

Timestamp: [01:27:02](https://youtu.be/LY0H8sBnbZY?t=5231)

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