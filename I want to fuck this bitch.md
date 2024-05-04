---
Origin: "[[After Dark 131]]"
Person: "[[Fidias]]"
Requested By: 
tags:
  - Soundbite
---
> *"I want to fuck this bitch"*

Timestamp: [01:29:14](https://www.youtube.com/watch?v=evmZ3TGPbbk&t=5349s)

# ADDITIONAL INFO
[https://www.reddit.com/r/h3h3productions/comments/18hwojc/fidias_dropping_some_hot_new_sound_bites/](https://www.reddit.com/r/h3h3productions/comments/18hwojc/fidias_dropping_some_hot_new_sound_bites/ "https://www.reddit.com/r/h3h3productions/comments/18hwojc/fidias_dropping_some_hot_new_sound_bites/") @ 0:10

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