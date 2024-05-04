---
Origin: "[[Podcast 21]]"
Person: "[[Vin Diesel]]"
tags:
  - Soundbite
---
> *"Someone Save Me!"*

Timestamp: [00:21:57](https://youtu.be/MBZC4FxMQ_E?t=1317)

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