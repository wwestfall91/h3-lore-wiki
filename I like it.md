---
Origin: "[[Podcast 155]]"
Person: "[[Ethan]]"
Requested By:
  - write-a-slick-song
On H3Lore?: false
tags:
  - Soundbite
---
> *"I like it"*

Timestamp: [01:23:10](https://youtu.be/AkJZcJhh7qQ?t=4990)

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