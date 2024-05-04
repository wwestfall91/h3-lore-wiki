---
Origin: "[[OTR 89]]"
Person: "[[BigNik]]"
Requested By: 
tags:
  - Soundbite
---
> *"He sings badly"*

Timestamp: [01:50:34](https://youtu.be/YmbtrKQIgd8?t=6634)

# ADDITIONAL INFO

OG Video: [Jimmy Levy - Freedom (Official Music Video) - YouTube](https://www.youtube.com/watch?v=xGe4cD8u8xQ)
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