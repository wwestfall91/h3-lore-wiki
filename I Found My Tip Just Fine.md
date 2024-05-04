---
Origin: "[[H3TV 103]]"
Person: "[[Tipster]]"
tags:
  - Soundbite
---
> *“I Found My Tip Just Fine When I was giving it to your FUCKING MOM”*

Timestamp: [03:28:30](https://youtu.be/WuaEyOStUds?t=12510)

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