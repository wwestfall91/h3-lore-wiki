---
Origin: "[[Podcast 15]]"
Person: "[[Bill Cosby]]"
tags:
  - Soundbite
---
> *"Soundbite"*

Timestamp: [01:15:50](https://youtu.be/GSZYeL84t90?t=4550)

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