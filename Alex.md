---
Friend?: 
Enemy?: 
tags:
  - Person
---
# ABOUT ME
An old crew member that wasn't on the show very long
# EPISODES
``` dataview
TABLE
FROM "Episodes"
WHERE 
contains(Topics.file.path, this.file.path) 
OR 
contains(file.outlinks.file.path, this.file.path)
OR
contains(file.inlinks.file.path, this.file)
AND
!contains(row["Guest(s)"].file.path, this.file.path) 
GROUP BY file.link
```

# ADDITIONAL NOTES
