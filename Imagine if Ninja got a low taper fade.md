---
Origin: "[[OTR 100]]"
Person: "[[EricDoa]]"
tags:
  - Soundbite
---
> *"Imagine if [[Ninja|Ninja]] Got a Low Taper Fade"*

Timestamp: [01:39:55](https://youtu.be/cfZM73q7NOc?t=5995) - Full Segment
# ADDITIONAL INFO
[First Drop](https://youtu.be/cfZM73q7NOc?t=401)
[OG TikTok](https://www.tiktok.com/@ericdoaclips/video/7322891263286529311)

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