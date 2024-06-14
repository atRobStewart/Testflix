---
date: 2024-06-06 13:13:58
layout: post
title: ""
description: You are tasked with babysitting a seemingly normal baby, but as the game unfolds not all is as it seems with sublte horror events that escalate over the chapters revealing the babys attempts to take control.
image: https://gaming-cdn.com/images/products/14267/orig/the-baby-in-yellow-pc-game-steam-cover.jpg?v=1697641227
category: Baby in Yellow
tags: 
  - team terrible
  - comedy horror
  - lovecraftian
author: robstewart
paginate: false
---
The following are some bugs and glitches I found during my hilariously terrifying playthrough of The Baby in Yellow. My restrictions to the free mobile version have made deep probing of the game more difficult than anticipated. I don't usually play mobile games, but I'm enjoying the new challenges it presents. The game is in early access, so once I get past my initial enjoyment, I'm anticipating that I'll find several bugs. So far, this game is excellent. I love the aesthetic and the horror-comedy aspect of it, and the dash of puzzling mixed in complements this game well, generating a nice, smooth pace.


## Episode 1
### Google playstore screen overlay tricks the auto pause function

| Platform | Hardware | Software  | Chapter       | Mission  |
| ---------| -------- | --------- | ------------- | -------- |
| Mobile   | Razor 1  | Android 9 | Rabbit - Exit | Survive! |

| Bug Severity | Priority level |
| ------------ | -------------- |
| Minor        | Low            |

<iframe width="560" height="315" src="https://www.youtube.com/embed/dzBZjVxtySg?si=1kPzVqfRjLU2KqPH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

| Description (Captured on the 06/06/2024) |
| :-- |
| On trying to open the achievements menu on the pause screen, google prompts you to create a Play Games account. |
| When you cancel this, you are returned to the game, but it continues to run even though it's on the pause screen. |
| The game continues to run even when you die and restart, and when you open up different menus and submenus. |
| The bug is easy to replicate by resuming and pausing again, and trying to open up the achievements. This is demonstrated at the 1:03 mark onwards. |

## Episode 2
### Coming Soon! (once I get over my skill issue on mobile)

## Blog

### Episode 1
Bug severity is **minor** with a **low** priority level. This was tough to gauge and is open to the opinions of a triage. My reasoning for going low with both ratings is because it seems specific steps are needed to execute it, and it doesn't break the game or cause the player to lose a lot of progress. The checkpoint system is forgiving. My guess as to why this is happening is that the game auto-pauses if any action, like an app pop-up or a phone call, drags you out of the game, a well-thought-out piece of functionality to put in a game, especially on the mobile version. But it seems like it doesn't recognise if the game is already paused when this happens, so in this particular instance, the software is executing the pause command and is resuming the game instead, causing it to run underneath the menu.