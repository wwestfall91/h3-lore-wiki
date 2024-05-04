---
Friend?: 
Enemy?: 
tags:
  - Person
---
# ABOUT ME
Pickup artist.

Entire H3H3 video about him - [[./The Greatest YouTuber of ALL TIME|The Greatest YouTuber of ALL TIME]]

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
