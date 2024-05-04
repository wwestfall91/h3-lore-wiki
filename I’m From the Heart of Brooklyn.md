---
Origin: "[[H3TV 105]]"
Person: "[[Ethan Bradberry]]"
tags:
  - Soundbite
---
> *"I'm from the HEART OF BROOKLYN!"*

Timestamp: [00:19:33](https://youtu.be/k1VrTaTohWA?t=1173)

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