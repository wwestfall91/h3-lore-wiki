---
Origin: "[[Podcast 21]]"
Person: "[[Vin Diesel]]"
tags:
  - Soundbite
---
> *Various other noises from Vin Diesels creepy interview*

Timestamp: [00:18:01](https://youtu.be/MBZC4FxMQ_E?t=1081)

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