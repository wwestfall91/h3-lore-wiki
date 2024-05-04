---
Origin: "[[H3TV 113]]"
Person: "[[Richard Simmons]]"
tags:
  - Soundbite
---
> His foot got run over by a card

Timestamp: [02:03:53](https://youtu.be/zkoKnz5zE3o?t=7433)

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