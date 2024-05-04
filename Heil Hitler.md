---
Origin: "[[OTR 40]]"
Person: "[[Dan]]"
Requested By: 
On H3Lore?: false
tags:
  - Soundbite
---
> *"Heil Hitler"*

Timestamp: [02:31:58](https://youtu.be/ue2zpTPkthg?t=9118)

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