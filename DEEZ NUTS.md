---
Origin: "[[After Dark 99]]"
Person: "[[Donna Klein]]"
On H3Lore?: 
tags:
  - Soundbite
---
> *"DEEEEZ NUTS"*

Timestamp: [02:48:20](https://youtu.be/FkTrjT_PDDc?t=10100)

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