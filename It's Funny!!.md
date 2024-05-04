---
Origin: 
Person: "[[Ethan]]"
Requested By: 
On H3Lore?: false
tags:
  - Soundbite
---
> *"Its funny!"*

Timestamp: [00:00:00]

# ADDITIONAL INFO
Played on [[./Podcast 170|Podcast 170]] around the 1:40:00 mark

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