---
Origin: "[[H3TV 103]]"
Person: "[[Jake Doolittle]]"
tags:
  - Soundbite
---
> *"Nooo, Ethan - That's Not How That Works!"*

Timestamp: [02:46:52](https://youtu.be/WuaEyOStUds?t=10012)

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