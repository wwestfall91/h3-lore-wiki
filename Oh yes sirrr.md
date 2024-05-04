---
Origin: 
Person: "[[Dash Dobrofsky]]"
Requested By:
  - Dw
tags:
  - Soundbite
---
> *"Oh yes sirrr"*

Timestamp: [00:00:00]

# ADDITIONAL INFO

> *I think it may have been BBQ related? It repeats in the same way that the Oh Boy Big News soundbite does. Zach sometimes plays it after the Oh Boy Big News soundbite. And I think he played it on one of the last shows when they were watching the Tiktokker who had all the videos about what men do, with the same intro.*
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