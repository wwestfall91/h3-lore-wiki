---
Origin: 
Person: "[[Owen Wilson]]"
Requested By:
  - bekahrama
tags:
  - Soundbite
---
> *"This is the first time. For ME. IN. The. Marvel Universe."*

Timestamp: [00:00:00]

# ADDITIONAL INFO

> *H3 After Dark #41*

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