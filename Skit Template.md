---
Rating (1-10): 
tags:
  - Skit
---
> *High level Description*

Additional Details
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