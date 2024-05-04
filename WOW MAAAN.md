---
Origin: "[[Podcast 21]]"
Person: "[[Vin Diesel]]"
tags:
  - Soundbite
---
> *"Wowwww Maaaaan"*

Timestamp: [00:19:53](https://youtu.be/MBZC4FxMQ_E?t=1193)

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