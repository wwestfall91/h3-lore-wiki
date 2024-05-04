---
Video Name: 
Creator: 
Topic(s): 
URL: 
tags:
  - Video
---
> *High level Description*

Additional Details
# WATCHED ON:
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