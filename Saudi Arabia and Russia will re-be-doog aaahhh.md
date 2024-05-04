---
Origin: 
Person: "[[Donald Trump]]"
Requested By: 
On H3Lore?: false
tags:
  - Soundbite
---
> *"Soundbite"*

Timestamp: [00:00:00]

# ADDITIONAL INFO
>*[I love a new Trump soundbite : r/h3h3productions](https://www.reddit.com/r/h3h3productions/comments/1b7e56a/i_love_a_new_trump_soundbite/?rdt=50643)*
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