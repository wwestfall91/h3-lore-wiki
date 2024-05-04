---
Origin: "[[Podcast 75]]"
Person: "[[Roseanne Barr]]"
tags:
  - Soundbite
---
> *"I THOUGHT THE BITCH WAS WHITE! **GOD DAMMIT!!!**"*

Timestamp: [01:08:26](https://youtu.be/pKENOdgWWUY?t=4106)

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