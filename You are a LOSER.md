---
Origin: "[[OTR 57]]"
Person: "[[Brantley]]"
tags:
  - Soundbite
---
> *"You are a LOSER!"*

Timestamp: [01:32:20](https://youtu.be/txuivldLEzo?t=5540)

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