---
Origin: 
Person: "[[Dan]]"
Requested By:
  - deniaal_2r
tags:
  - Soundbite
---
> *"Stomp on his Dick"*

Timestamp: [00:00:00]

# ADDITIONAL INFO

> *Highlights channel video titled "Ethan On The iDubbbbz Controversy" @8:45*

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