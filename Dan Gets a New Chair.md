---
tags:
  - Segment
---

> *We say goodbye to the scorpion chair on this fateful day*

Viewers vote to decide which chair will replace the [[./Scorpion Chair|Scorpion Chair]]
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