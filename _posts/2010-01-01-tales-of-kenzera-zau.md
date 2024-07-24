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
  - surgent studios
  - ea originals
  - metroidvania
author: robstewart
paginate: false
---
The following are bugs and glitches I found during my playthrough of Tales of Kenzera: Zau, presented in episodic fashion. Being a side-scrolling Metroidvania made it a more difficult game to find bugs in with the lack of z-axis interactability, but considering it's new, I knew bugs would be inevitable, and ultimately, this game didn't disappoint. I will also note that this game is an absolute gem and has a stunning amount of character, personality, and identity. I was hooked from start to finish, except for the break I had to take. Speaking of which, let's get to the first episode.
<br>
Blog section after the last episode goes into detail on my thoughts about each episode and is more personally written.



## Episode 1 (Bug has been fixed)
### Act 2 Great Spirit chase sequence soft lock

| Platform      | Firmware          | Software | Location       | Mission |
| ------------- | ----------------- | -------- | -------------- | ------- |
| PlayStation 5 | 24.03-09.20.00.05 | 1.1      | Under Wildwood | Escape  |

| Bug Severity | Priority level |
| ------------ | -------------- |
| Major        | Critical       |

<iframe width="560" height="315" src="https://www.youtube.com/embed/fudmDtAomR4?si=hn8RSOKoAGGuz1SC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

| Description (Captured on 19/05/2024) |
| :-- |
| If you climb the wall to the right instead of going left as the game intended, an unbreakable rock appears on the pathway, blocking the player from progressing. |
| The rock loads in off-screen, so it is difficult to determine what caused it with no access to the game log files. |
| The best assumption is that a trigger point along the right-side pathway loaded it in. |
| My guess is that when you reach the end of the pathway, the dialog and autosave load the rock in to prevent players who went left initially from following the path again and going around in circles. |



## Episode 2 (Bug has been fixed)
### Lost movement input on exiting map


| Platform      | Firmware          | Software | Location         | Mission         |
| ------------- | ----------------- | -------- | ---------------- | --------------- |
| PlayStation 5 | 24.03-09.20.00.05 | 1.0      | The Great Cliffs | Follow the Girl |

| Bug Severity | Priority level |
| ------------ | -------------- |
| Minor        | Medium         |

<iframe width="560" height="315" src="https://www.youtube.com/embed/lKbJ4zdh-CE?si=Y6hNtKFQnju9-Wbu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

| Description (Captured on 07/05/2024) |
| :-- |
| When closing the map, Zau does not continue to move in the direction you're holding. |
| It's difficult to convey this in the video, but you can see that he can still look around and jump on the spot. |
| It is easy to fix; simply release the directional stick, and it will reset the input command. |
| Very easy to replicate, it will happen every time when exiting the map screen. |



## Episode 3
### Unresponsive enemies


| Platform      | Firmware          | Software | Location         | Mission                       |
| ------------- | ----------------- | -------- | ---------------- | ----------------------------- |
| PlayStation 5 | 24.03-09.20.00.05 | 1.1      | Ember's Spring   | Journey towards Mount Itshoka |

| Bug Severity | Priority level |
| ------------ | -------------- |
| Minor        | Low            |

<iframe width="560" height="315" src="https://www.youtube.com/embed/PCbYPM5ZMxg?si=dcvOoTmYXk8MoUbK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

| Description (Captured on 28/05/2024) |
| :-- |
| During combat, if an enemy receives an attack while off-screen, it becomes unresponsive. |
| It only performs its idle animation. |
| Further attacks on the enemy don't cause it to attack. |
| The enemy can still be killed, so this can be exploited. |



## Episode 4
### Keep aiming with holding the L2 button down

| Platform      | Firmware          | Software | Location  | Mission             |
| ------------- | ----------------- | -------- | --------- | ------------------- |
| PlayStation 5 | 24.03-09.20.00.05 | 1.1      | Woodlands | Return to Sabulana  |

| Bug Severity | Priority level |
| ------------ | -------------- |
| Minor        | Medium         |

<iframe width="560" height="315" src="https://www.youtube.com/embed/1HRVr7qD0vk?si=WA-sFWAvSq3YrdPP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

| Description (Captured on 19/05/2024) |
| :-- |
| While aiming projectiles by holding the L2 button down and moving the left stick, if an overlay pops up while doing this, Zau will get stuck in this state. |
| The aim movement being mapped to the left stick now prevents a player from moving Zau. |
| It's easy to fix by pressing and releasing L2 again. |
| It is also easy to replicate by opening the map and releasing L2 while on the map screen. |
| This bug is similar to the one found in episode 2. Note that it wasn't picked up in the 1.1 patch. |

## Blog

### Episode 1
The severity level is **major** with a **critical** priority. This bug soft locks the player indefinitely. Thanks to the autosave and a lack of manual saving, there is no way for the player to revert to a point before the soft lock, with the exception of restarting the entire game, not ideal for most. Anything that stops players in their tracks like this should get the highest priority because it can bring about a lot of negative publicity, causing an otherwise great game to get review bombed. I have stopped playing until a patch is rolled out for it.
 <br>
 **Update:** The bug got fixed a few days after I found it, as of the version 1.1.1 update. It was great to see a fix rolled out so quickly for it. 
 <br/>

### Episode 2
 The severity level is **minor** but with a **medium** priority. At first, I rated it a low priority, but the more I played the game and realised how much I used the map, the more frustrating the bug became. It isn't a severe bug; it doesn't break the game or cause the player to get stuck. It's just that, with how easy it is to replicate, the repetition of executing it slowly raises blood pressure over time.
<br>
**Update:** This bug was fixed with the 1.1 version update. Considering I've never come across it in similar games, it's good to see that it got recognised quickly. Surgent Studios deserves great credit for their speed in dealing with these issues. 
<br/>

### Episode 3
The severity level is **minor** with a **low** priority level. I do have a few videos demonstrating this bug with different enemies, but I never found myself actively exploiting it; I just stumbled into it. Usually, fights are chaotic with several enemies on-screen, so active exploitation would be tricky at the best of times. Furthermore, people usually welcome a bug that makes a game easier, so I don't think there's any need to hurry with a fix, especially if there are more important fixes to resolve. However, it should get fixed eventually.

### Episode 4
The severity level is **minor** but with a **medium** priority. This bug is similar to the one found in episode 2, but it was much more difficult to find in comparison, as its occurrence is primarily battle-specific, whereas episode 2's centered around movement. Given how long it took me to find it comparatively, I feel a low priority would be enough, but because of the similarity, I think medium is justified to bring more attention to the nature of the bug and get the QA team to find any more potential instances of it occurring.