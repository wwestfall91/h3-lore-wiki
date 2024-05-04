---
Origin: 
Person: "[[Jordan Peterson]]"
Requested By:
  - Nurpus
tags:
  - Soundbite
---
> *"Baby want!"*

Timestamp: [00:00:00]

# ADDITIONAL INFO

>*Some of them are here: [https://youtu.be/AuHjVvegRs8?si=rivNAzSmUyI11Fhh](https://youtu.be/AuHjVvegRs8?si=rivNAzSmUyI11Fhh "https://youtu.be/AuHjVvegRs8?si=rivNAzSmUyI11Fhh")*
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