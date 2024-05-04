---
Origin: "[[OTR 99]]"
Person: "[[Joe Rogan]]"
tags:
  - Soundbite
---
> *This is where woke meets the wall*

Timestamp: [01:47:43](https://youtu.be/GBj19zjrWzQ?t=6463)

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