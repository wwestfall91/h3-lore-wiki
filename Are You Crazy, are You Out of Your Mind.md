---
Origin: "[[Podcast 32]]"
Person: Unknown
tags:
  - Soundbite
---
> *"What are you, crazy?! Are you out of your mind?!"*

Timestamp: [01:11:22](https://youtu.be/GUdGWhfpuoY?t=4282)

# ADDITIONAL INFO
While we do not know the man who said it, it originated from a [[./Colby Persin|Colby Persin]] video

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