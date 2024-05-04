---
Origin: "[[After Dark 101]]"
Person: "[[SunnyV2]]"
Requested By: 
tags:
  - Soundbite
---
> *"Gayh!"*

Timestamp: [02:10:34](https://youtu.be/r6vG1VKGnOo?t=7826)

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