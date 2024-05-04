---
Origin: 
Person: Misc
Requested By: 
On H3Lore?: false
tags:
  - Soundbite
---
> *... Crickets churping ...*

Timestamp: [00:00:00]

# ADDITIONAL INFO

>*it’s just the crickets sound*
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