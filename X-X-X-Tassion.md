---
Origin: "[[Content Court]]"
Person: "[[Ethan]]"
tags:
  - Soundbite
---
> *"X-X-X-Tassion"*

Timestamp: [00:05:14](https://www.youtube.com/watch?v=VQ6bqvWmHoo&t=314s)

# ADDITIONAL INFO

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