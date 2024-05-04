---
Origin: 
Person: "[[Alki David]]"
Requested By: Suigetsushin
tags:
  - Soundbite
---
> *"Shut up BITCH"*

Timestamp: [00:00:00]

# ADDITIONAL INFO
[Alki David owns DJ Keemstar - YouTube](https://www.youtube.com/watch?v=Wn8p274mHnU)

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