---
Origin: "[[OTR 87]]"
Person: "[[Lil Mo]]"
Requested By:
  - annawillcrane
tags:
  - Soundbite
---
> *"A crane fuckin smashed him right in his head"*

Timestamp: [03:04:10](https://www.youtube.com/watch?v=R8Y-ih8DLlc&t=11049s)

# ADDITIONAL INFO
[A crane fuckin smashed him right in his head : r/h3h3productions](https://www.reddit.com/r/h3h3productions/comments/1bl6kbx/a_crane_fuckin_smashed_him_right_in_his_head/)
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