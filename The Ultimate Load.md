---
Origin: "[[OTR 107]]"
Person: "[[Jordan Peterson]]"
tags:
  - Soundbite
---
> *"Soundbite"*

Timestamp: [01:28:01](https://youtu.be/7H2vgnSz0tg?t=5281)

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