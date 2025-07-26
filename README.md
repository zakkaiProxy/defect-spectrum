# Defect spectrum
A game development guide for tracking bugs based on software engineering error naming conventions

## Why a guide?
The purpose of knowing the name of your bugs is not only to know a "name" by itself but to identify where to track it and how bad does it affect your game in the stage of development where you find it, how much time, cost, and effort will it take you to fix it, and how bad does it affect your players.

As solo-devs we might think ***"Well if there is a bug in my game why would I overlook it and not fix it?"*** 

Some bugs are present in your game but only become visible after a combination of actions from the player. These are addresed as `defects`. But if that doesn't happen, the bug will exist at all stages of development of your game `latent defects`. Sometimes that's ok, sometimes it is not.

![](https://github.com/zakkaiProxy/defect-spectrum/blob/main/blueprint/defect-spectrum.png)

# 🎮Game developer/tester challenge🎴 

-How fast can you name which are `errors`, which are `faults`, which are `failures` and which are `defects` ? 👾 ✖️ 

Kip's indie studio is working on a prototype for a "portal" type game. During early testing, the game presented a `    1    ` when generating portals, since the player's camera cannot see what the second portal projects from the projection of the first portal. After investigating the problem, Kip discovered that this was Case's
`    2    ` , a graphics programmer, who due to lack of time did not implement his recursive rendering algorithm to the game engine, causing a `    3    ` in the game, since to pass 60% of the levels, you need to use the portals as mirrors to see hidden areas.

After implementing Case's function, the game presented a rendering `    4    ` when calculating the distance between objects and image projections, causing the projection to recursively appear 7 meters above the second portal with shadows and distortions of the shapes through the first portal final projection.

Case may have made other `    5    ` during development and there may be more latent `    6    ` in the game's lighting.

# ⛰️Challenge Answers💡 

Kip's indie studio is working on a prototype for a "portal" type game. During early testing, the game presented a hashtag `fault` when generating portals, since the player's camera cannot see what the second portal projects from the projection of the first portal. After investigating the problem, Kip discovered that this was Case's `error`, a graphics programmer, who due to lack of time did not implement his recursive rendering algorithm to the game engine, causing a `defect` in the game, since to pass 60% of the levels, you need to use the portals as mirrors to see hidden areas.

After implementing Case's function, the game presented a rendering hashtag `failure` when calculating the distance between objects and image projections, causing the projection to recursively appear 7 meters above the second portal with shadows and distortions in the shapes through the first portal final projection.

Case may have made other hashtag `errors` during development and there may be more latent hashtag `defects` in the game's lighting.

