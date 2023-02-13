---
layout: post
title: Testing Jekyll again
date: 2023-02-09 16:32
category: 
author: wim vinckier
tags: [code]
summary: 
---

# Jekyll on Visual Studio Code

Never thought I would ever do it but I did.  Based on [this port][JekyllPost] I've installed some nice plugins hoping to post more news this year.

I'm wondering if it will help me to post more messages.

[JekyllPost]: https://www.mslinn.com/jekyll/5300-vscode-ext-jekyll.html

```
docker run --rm -it \
  --volume="${PWD}:/srv/jekyll" \
  --volume="${PWD}/vendor/bundle:/usr/local/bundle" \
  -p 4000:4000 jekyll/jekyll:3.8 \
  jekyll serve
```
