---
URL: https://www.youtube.com/@h3animated
tags:
  - Person
---
# ABOUT ME
The unofficial channel for animated clips of the H3 Podcast & more!
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
