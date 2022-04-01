---
title: "One Liners"
date: 2022-04-01T06:10:53-04:00
draft: false
tags: []
author: "Greg Peddle"
hidden: true
---

Here is a collection of Linux one-liners that have been useful.
Stored here as a personal reference.

----

### Fix Chromium 'boxes' 

Chromium browser was showing 'boxes' instead of characters when browsing to upload files.
Resetting the font cache fixed this. Reboot was not required.

`fc-cache -fr`

----