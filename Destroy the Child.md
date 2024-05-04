---
Origin: "[[Podcast 77]]"
Person: "[[Alex Jones]]"
tags:
  - Soundbite
---
> *"Soundbite"*

Timestamp: [00:26:35](https://youtu.be/fA8eOB91-fY?t=1593)

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