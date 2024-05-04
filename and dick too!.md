---
Origin: "[[After Dark 119]]"
Person: "[[Barack Obama]]"
Requested By: 
tags:
  - Soundbite
---
> *"and dick too!"*

Timestamp: [00:04:34](https://youtu.be/uJVzxi2WNGw?t=274)

# ADDITIONAL INFO

> *[https://www.youtube.com/live/uJVzxi2WNGw?si=oIGtz6kAikfsSTNj](https://www.youtube.com/live/uJVzxi2WNGw?si=oIGtz6kAikfsSTNj "https://www.youtube.com/live/uJVzxi2WNGw?si=oIGtz6kAikfsSTNj") 4:31, zach plays it again a bit after where nobody speaks so its fully isolated*

## Episodes
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