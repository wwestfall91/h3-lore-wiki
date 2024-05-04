---
Origin: 
Person: "[[Carlos Matos]]"
tags:
  - Soundbite
---
> *"The World is Not Anymore the Way it Used to Be. Mmmm, no, no, no!"*

Timestamp: [00:01:51](https://www.youtube.com/watch?v=EhL2OWXZ26s&t=110s)

It was first dropped on the Podcast on [[./Podcast 47|Podcast 47]], but there the H3H3Productions video predates it.
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