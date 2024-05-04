---
Origin: 
Person: "[[Donald Trump]]"
Requested By: 
tags:
  - Soundbite
---
> *"Soundbite"*

Timestamp: [00:00:00]

# ADDITIONAL INFO

> *It was from a recent rally when he tripped over his words and let out a weird moan. It was in the last few months but I can't find exactly which episode.*

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