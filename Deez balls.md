---
Origin: 
Person: "[[Ryan Kavanaugh]]"
Requested By: 
On H3Lore?: false
tags:
  - Soundbite
---
> *"Soundbite"*

Timestamp: [00:00:00]

# ADDITIONAL INFO

>*It's recent, since the failure podcast was started I believe. It may be an AI voice line? I think he says "hey suck deez balls" or something similar*
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