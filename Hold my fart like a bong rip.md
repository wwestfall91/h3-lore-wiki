---
Origin: "[[OTR 109]]"
Person: "[[Candace Owens]]"
Requested By:
  - simplefactothematter
On H3Lore?: 
tags:
  - Soundbite
---
> *"Hold my fart like a bong rip"*

Timestamp: [00:07:00](https://www.youtube.com/watch?v=VN3bWz5HfBI&t=420s)

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