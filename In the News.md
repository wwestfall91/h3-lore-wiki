---
tags:
  - Segment
---

> *A very early segment that was given to none of the than Dan the Producer!*

[[./Dan|Dan]]'s first ever segment
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