---
URL: https://www.youtube.com/@zachandwahlid
tags:
  - Person
---
# CHANNEL DESCRIPTION
Everyone needs a best friend! Join Zach and Wahlid each week as they reveal their hilarious stories, debate the most inconsequential topics ever, and share their one-of-a-kind friendship with you – the newest member of this eternal friendship.
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
