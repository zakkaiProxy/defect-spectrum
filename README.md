# defect-spectrum
A game development guide for tracking bugs based on software engineering error naming conventions

![](https://github.com/zakkaiProxy/defect-spectrum/blob/main/blueprint/defect-spectrum.png)

# 🎮Game developer/tester challenge🎴 

-How fast can you name which are errors, which are faults, which are failures and which are defects? 👾 ✖️ 

Kip's indie studio is working on a prototype for a "portal" type game. During early testing, the game presented a `____1____` when generating portals, since the player's camera cannot see what the second portal projects from the projection of the first portal. After investigating the problem, Kip discovered that this was Case's `____2____` , a graphics programmer, who due to lack of time did not implement his recursive rendering algorithm to the game engine, causing a `____3____` in the game, since to pass 60% of the levels, you need to use the portals as mirrors to see hidden areas.

After implementing Case's function, the game presented a rendering `____4____` when calculating the distance between objects and image projections, causing the projection to recursively appear 7 meters above the second portal with shadows and distortions of the shapes through the first portal final projection.

Case may have made other `____5____` during development and there may be more latent `____6____` in the game's lighting.

