---
Origin: "[[./Podcast 20|Podcast 20]]"
Person: "[[Ethan]]"
tags:
  - Soundbite
---
> *"Fascinating!"*

Timestamp: [00:02:23](https://youtu.be/rq8HL3jVy-M?t=143)

# ADDITIONAL INFO
Early on in the Podcast Ethan would use fascinating as his filler word ALL THE TIME. On [[./Podcast 19|Podcast 19]] Ethan discusses how viewer pick on him for saying it so much. This would prompt Dan to make it a soundbite that is used on [[./Podcast 20|Podcast 20]]. This would be the very first soundbite to ever come from a crew member!

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