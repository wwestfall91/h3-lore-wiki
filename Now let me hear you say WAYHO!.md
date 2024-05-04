---
Origin: "[[H3TV 81]]"
Person: 
Requested By: 
tags:
  - Soundbite
---
> *"boom boom boom, now let me hear you say WAYHO!"*

Timestamp: [00:21:50](https://www.youtube.com/watch?v=bD3yMLPhozo&t=1309s)

# ADDITIONAL INFO
[OG Video](https://www.youtube.com/watch?v=wXKKlNoNdQY)

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