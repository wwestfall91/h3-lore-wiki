---
Origin: "[[H3TV 82]]"
Person: "[[Colleen Ballinger]]"
Requested By: 
On H3Lore?: false
tags:
  - Soundbite
---
> *"(I made a) **Fart Joke!**"*

Timestamp: [02:12:58](https://youtu.be/eb8z8kaekfw?t=7978)

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