---
Origin: 
Person: "[[Love]]"
Requested By: 
tags:
  - Soundbite
---
> *"There's cum everywhere in my room"*

Timestamp: [00:00:00]

# ADDITIONAL INFO

> *Soundbite where loves says "there's cum everywhere in my room", at some point Zach played it and I think love told him not to play it anymore, but after a year or so he now occasionally plays it and love laughs.*
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