---
layout: post
title: "how to download videos from sharepoint"
---

# how to download videos from sharepoint

1. open the link and find in the network inspection tab the resource filtering with this field: `&altManifestMetadata` 
2. after that, copy the source url and delete all parameters after that field
3. open the terminal and execute this command:



```bash
ffmpeg -i "url-obtained" -codec copy video.mp4 
```


and there you go :) 
