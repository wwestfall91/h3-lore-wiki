---
Origin: "[[OTR 57]]"
Person: "[[Janitor Yelling at AB]]"
tags:
  - Soundbite
  - "#SkateBoard"
---
> *"REAL FUNNY HUH, WHOSE LAUGHING NOW?!"*

Timestamp: [01:33:35](https://youtu.be/txuivldLEzo?t=5615)


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