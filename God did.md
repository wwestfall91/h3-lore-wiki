---
Origin: "[[After Dark 91]]"
Person: "[[DJ Khaled]]"
Requested By: 
tags:
  - Soundbite
---
> *"God did"*

Timestamp: [01:51:17](https://www.youtube.com/watch?v=lUP64bI7INk&t=6665s)

# ADDITIONAL INFO

>*Look for video of him powerwashing beside the pool*
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