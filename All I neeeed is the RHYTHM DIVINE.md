---
Origin: "[[OTR 96]]"
Person: "[[Enrique Iglesias]]"
tags:
  - Soundbite
---
> *♪ AlLlL I NeeEEEd iS the RYThM DIViNE ♪*

Timestamp: [00:12:23](https://youtu.be/Z17qb2ybiuI?t=743)

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