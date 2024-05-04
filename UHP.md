---
Origin: "[[OTR 105]]"
Person: "[[Jimmie Lee]]"
tags:
  - Soundbite
---
> *"UHHHHPpp..."*

Timestamp: [00:18:16](https://youtu.be/8ZkY_nHj3vY?t=1096)

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