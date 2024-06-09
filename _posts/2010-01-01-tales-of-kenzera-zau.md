---
date: 2023-09-18T13:48:05.000Z
layout: post
title: ""
description: >-
  You play as a young shaman named Zau who must capture spririts for the God of Death, Kalunga, who in return has promised to revive his dead father.
image: >-
  https://media.contentapi.ea.com/content/dam/ea/tales-of-kenzera/zau/common/olorun-fpo-feat-img.png.adapt.crop16x9.1023w.png
category: Tales of Kenzera Zau
tags:
  - stormcloud studios
  - ea originals
  - metroidvania
author: robstewart
paginate: false
---
Here's the revised text with improved punctuation:

The following are bugs and glitches I found during my playthrough of Tales of Kenzera: Zau. Being a side-scrolling Metroidvania made it a more difficult game to find bugs in with the lack of z-axis interactability, but considering it's new, I knew bugs would be inevitable, and ultimately, this game didn't disappoint. I will also note that this game is an absolute gem and has a stunning amount of character, personality, and identity. I was hooked from start to finish, except for the break I had to take. Speaking of which, let's get to the first episode.



## Episode 1 (Bug has been fixed)
### Act 2 Great Spirit chase sequence soft lock (Captured on 19/05/2024)

| Platform      | Firmware          | Software | Location       | Mission |
| ------------- | ----------------- | -------- | -------------- | ------- |
| PlayStation 5 | 24.03-09.20.00.05 | 1.1      | Under Wildwood | Escape  |

| Bug Severity | Priority level |
| ------------ | -------------- |
| Major        | Critical       |

<iframe width="560" height="315" src="https://www.youtube.com/embed/fudmDtAomR4?si=hn8RSOKoAGGuz1SC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

| Description |
| :-- |
| If you climb the wall to the right instead of going left as the game intended, an unbreakable rock appears on the pathway, blocking the player from progressing. |
| The rock loads in off-screen, so it is difficult to determine what caused it with no access to the game log files. |
| The best assumption is that a trigger point along the right-side pathway loaded it in. |
| My guess is that when you reach the end of the pathway, the dialog and autosave load the rock in to prevent players who went left initially from following the path again and going around in circles. |



## Episode 2
### Coming Soon!


## Blog

### Episode 1
The severity level is **major** with a **critical** priority. This bug soft locks the player indefinitely. Thanks to the autosave and a lack of manual saving, there is no way for the player to revert to a point before the soft lock, with the exception of restarting the entire game, not ideal for most. Anything that stops players in their tracks like this should get the highest priority because it can bring about a lot of negative publicity, causing an otherwise great game to get review bombed.
 <br>
 **Update:** The bug got fixed a few days after I found it, as of the version 1.1.1 update. It was great to see a fix rolled out so quickly for it