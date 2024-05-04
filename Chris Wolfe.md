---
Friend?: 
Enemy?: 
tags:
  - Person
---
# ABOUT ME
Reporter for KTLA, broke the original story with [[./Jake Paul|Jake Paul]] and [[./Team Ten|Team Ten]] being bad neighbors and causing complaints.

# GUEST EPISODES
``` dataview
TABLE
FROM "Episodes"
WHERE
contains(row["Guest(s)"].file.path, this.file.path) 
GROUP BY file.link
```

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

# SOUNDBITES
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

# ADDITIONAL NOTES
