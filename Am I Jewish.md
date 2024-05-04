---
Origin: "[[OTR 56]]"
Person: "[[Ninja]]"
Requested By: 
On H3Lore?: false
tags:
  - Soundbite
---
> *"Am I Jewishhh?"*

Timestamp: [00:20:45](https://youtu.be/0TyXVP4OYNM?t=1245)

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