---
Origin: "[[After Dark 131]]"
Person: "[[Fidias]]"
Requested By: 
tags:
  - Soundbite
---
> *"Margot Robbie…"*

Timestamp: [01:29:14](https://www.youtube.com/watch?v=evmZ3TGPbbk&t=5349s)

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