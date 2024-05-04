---
Origin: "[[Podcast 148]]"
Person: "[[Dan]]"
Requested By: 
On H3Lore?: true
tags:
  - Soundbite
---
> *"I'm so sorry to interrupt, we have to go to break"*

Timestamp: [00:34:19](https://youtu.be/NK-_XJBYv-c?t=2059)

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