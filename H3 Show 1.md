---
Title: 
Guest(s): 
Topics:
  - "[[PowerPoint|PowerPoint]]"
URL: 
Date: 
tags:
  - H3
---
# NOTES
[[Button|Button]] x2 during the ad read
#PowerPoint
#TopMoment - [[./Ethan|Ethan]] - “oh my god, I forgot what I looked like. AHHH!!””
## Timeline
- [ ] 

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
