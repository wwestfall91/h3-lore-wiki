---
Origin: "[[Podcast 1]]"
Person: "[[E-40]]"
Requested By:
  - maxster16
On H3Lore?: false
tags:
  - Soundbite
---
> *"Yup!"*

Timestamp: [00:00:00]

# ADDITIONAL INFO
*When they reference the E-40 song “Choices” using the iconic yup nope lyric.*
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