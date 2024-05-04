---
URL: https://www.youtube.com/@undeadmummy
tags:
  - Person
---
# ABOUT ME
I want to make mixed-media videos for a living. Willing to move for work.
# VIDEOS
``` dataview
TABLE
FROM "Videos"
WHERE 
contains(Creator.file.path, this.file.path) 
OR 
contains(file.outlinks.file.path, this.file.path)
OR
contains(file.inlinks.file.path, this.file)
AND
!contains(row["Guest(s)"].file.path, this.file.path) 
GROUP BY file.link
```

# WATCHED ON
``` dataview
TABLE
FROM "Episodes"
WHERE
contains(row["Guest(s)"].file.path, this.file.path) 
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
