---
Origin: 
Person: 
Requested By: 
On H3Lore?: false
tags:
  - Soundbite
---
> *"I think the angels threw her down and made sure she was not coming back!"*

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