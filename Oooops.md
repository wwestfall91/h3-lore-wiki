---
Origin: "[[H3TV 103]]"
Person: "[[Jake Doolittle]]"
tags:
  - Soundbite
---
> *"OoOooOops!"*

Timestamp: [03:37:26](https://youtu.be/WuaEyOStUds?t=13046)

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