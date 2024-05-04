---
Title: 
Guest(s): 
Topics: 
URL: 
Date: ""
tags:
  - H3
  - H3H3Productions
---
# NOTES


___
# NEW SOUNDBITES
``` dataview
TABLE
FROM "Soundbites"
WHERE 
contains(Topics.file.path, this.file.path) 
OR 
contains(file.outlinks.file.path, this.file.path)
OR
contains(file.inlinks.file.path, this.filep)
GROUP BY file.link
```
