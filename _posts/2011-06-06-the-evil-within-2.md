---
date: 2018-04-21 12:26:40
layout: post
title: ""
subtitle: 
description: Detective Sebastian Castellanos has lost everything, including his daughter, Lily. To save her, he must descend into the nightmarish world of STEM. Horrifying threats emerge from every corner, and he must rely on his wits to survive.
image: https://www.godisageek.com/wp-content/uploads/the-evil-within-2-listing-thumb-01-ps4-us-21sep17-1024x576.png
category: The Evil Within 2
tags:
  - tango gameworks
  - survival horror
  - placeholder
author: mranderson
paginate: false
---


I'm five years late to this game, so I played it in its final state. Any bugs found are here to stay, as Tango Gameworks has long since moved on, developing Ghostwire and HiFi Rush between 2017 and 2023. There are numerous textures and objects that pop in on camera, along with slow level of detail rendering—issues players regularly encounter. Although these are mostly cosmetic bugs, I've refrained from creating many episodes about them, as doing so would easily reach the hundreds.

## Episode 1

### Gets Stuck While Falling

| Platform      | Firmware        | Software | Chapter        | Location               |
| ------------- | --------------- | -------- | -------------- | ---------------------- |
| PlayStation 5 | v23.02-08.00.00 | 1.05     | 3. Resonances  | Union Residential Area |

| Bug Severity | Priority level |
| ------------ | -------------- |
| Minor        | Low            |

<iframe width="560" height="315" src="https://www.youtube.com/embed/P4t629aDWsI?si=_YlmHvK64VPW-vuu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

| Description |
| :-- |
| Sebastian begins climbing a crate with approximately half of his hitbox suspended in the air over the ground on completion. |
| This initiates his fall animation, but he remains caught on the crate because the other half of his hitbox is resting on it. |
| He stops the fall animation and briefly gets stuck on the crate before falling to the ground. There was no input from me to prompt Sebastian to complete the fall. |
| As a bonus bug, Sebastian clips into the higher crate during his climbing animation. It's minor and cosmetic, so it doesn't require its own episode. |



## Episode 2

### Snagged on Ground

| Platform      | Firmware        | Software | Chapter         | Location                |
| ------------- | --------------- | -------- | --------------- | ----------------------- |
| PlayStation 5 | v23.02-08.00.00 | 1.05     | 6. On the Hunt  | Union City Hall Outside |

| Bug Severity | Priority level |
| ------------ | -------------- |
| Minor        | Low            |

<iframe width="560" height="315" src="https://www.youtube.com/embed/_0MPqJKykas?si=Ic7ykJr1RLnLK0bZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

| Description |
| :-- |
| As Sebastian walks, he gets snagged on the ground. Like Episode 1, his fall animation briefly triggers, stops, and then he falls off a short ledge to his left. |
| This also occurs with no player input, except for moving the camera, once the snag is hit. |
| It appears that this issue can be triggered anywhere the player can change Sebastian's elevation. |
| Another bonus cosmetic bug: at the beginning of the video, you can plainly see the grass loading in. I won't be pointing out any more of these, as during development, they would each have their own reports and dedicated tracking. |







## Blog

### Episode 1
I would assign this issue a **minor** severity with a **low** priority. It is worth drawing reasonable attention to because it briefly takes control away from the player. This occurrence, albeit brief, succeeded in pulling me out of the game. Additionally, it prompted me to replicate the issue, which I managed to do successfully.

### Episode 2
This also receives a **minor** severity and **low** priority, as it mirrors the bug mentioned in Episode 1. While its reasonable frequency might argue for a moderate severity, it didn't occur frequently enough in my playthrough. Nevertheless, Sebastian's transition across different elevations should be revisited to address this bug, as it does temporarily take away control from the player.