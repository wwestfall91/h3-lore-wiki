---
tags:
  - Segment
---

[[./Internet Comment Etiquette|Internet Comment Etiquette]] had a very early segment on the show that in some ways could be considered the original [[PowerPoint|PowerPoint]] segment!
# APPEARANCES
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

# ADDITIONAL NOTES