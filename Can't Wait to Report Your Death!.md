---
Origin: "[[H3TV 30]]"
Person: "[[Keemstar]]"
Requested By: 
On H3Lore?: 
tags:
  - Soundbite
---
> *"Can't wait to report your death!"*

Timestamp: [01:23:45](https://www.youtube.com/watch?v=ulmY5h0M4co&t=5025s)

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