---
Origin: 
Person: "[[./Keemstar|Keemstar]]"
Requested By: 
tags:
  - Soundbite
---
> *"Shi..Shi..Shivola"*

Timestamp: [00:00:00]

# ADDITIONAL INFO
[[./Keemstar|Keemstar]] trying to say Chernobyl

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