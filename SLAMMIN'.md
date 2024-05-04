---
Origin: "[[Podcast 16]]"
Person: "[[Ethan Bradberry]]"
tags:
  - Soundbite
---
> ***"SLAAAAAAAAMMMMIN'"***

Timestamp: [00:28:53](https://youtu.be/N4k1gEC0800?t=1733)

# ADDITIONAL INFO
This was the very first soundbite ever used on the show.

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