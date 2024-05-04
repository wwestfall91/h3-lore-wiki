---
tags:
  - Topic
---

> *Early in the Podcast Ethan would ask every guest if they have any ghost stories*

An early name for this was "Spooks and Goofs", which Ethan uses [here](https://youtu.be/Z9U9TJ4W26k?t=4118) when crediting [[./Post Malone|Post Malone]] as the creator of it.
# APPEARANCES
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