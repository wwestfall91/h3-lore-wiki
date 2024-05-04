---
StoryTeller: "[[Ethan]]"
People Involved:
  - "[[Hila|Hila]]"
tags:
  - Story
Rating (1-10): 2
---
Ethan talks about how after the [[./Podcast 22|Jake Paul Episode]] they get home and 
# DISCUSSED ON
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