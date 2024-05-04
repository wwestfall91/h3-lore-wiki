---
Origin: "[[Podcast 21]]"
Person: "[[Vin Diesel]]"
tags:
  - Soundbite
---
> *"Soundbite"*

Timestamp: [00:19:24](https://youtu.be/MBZC4FxMQ_E?t=1164)

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