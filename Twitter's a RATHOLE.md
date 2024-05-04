---
Origin: 
Person: "[[Jordan Peterson]]"
Requested By: 
On H3Lore?: false
tags:
  - Soundbite
---
> *"Twitter's a RATHOLE"*

Timestamp: [00:00:00]

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