---
Origin: "[[H3TV 105]]"
Person: "[[Charlie Kirk]]"
tags:
  - Soundbite
---
> *"If I See a Black Pilot, I'm Gonna be Like 'Boy I hope He's Qualified'"*

Timestamp: [01:36:12](https://youtu.be/k1VrTaTohWA?t=5772)

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