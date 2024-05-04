---
Origin: "[[Podcast 171]]"
Person: "[[Ethan]]"
Requested By: 
On H3Lore?: false
tags:
  - Soundbite
---
> *"I don't like it"*

Timestamp: [01:56:37](https://youtu.be/XbeULz7ekV8?t=6997)

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