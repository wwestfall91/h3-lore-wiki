---
Origin: "[[H3 Show 1]]"
Person: "[[Just Tree]]"
Requested By: 
On H3Lore?: false
tags:
  - Soundbite
---
> *"Yayyyy, I got a subscriber!!"*

Timestamp: [01:14:16](https://www.youtube.com/watch?v=0lt0tTr-lj4&t=4454s)

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