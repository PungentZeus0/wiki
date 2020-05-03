# About this Document

This document is a work in progress, nothing here is considered even remotely final. Also, SuperTux uses version numbers instead of milestones now. There is a list of stuff that needs to be done, and at the bottom is a list of ideas that could be implemented too.

# Overview

SuperTux 0.7.0 will bring about a completion to the first two worlds so work can begin on World 3. This means improving/revamping the graphics, sound effects, code, story and levels in many areas and adding some new features/mechanics as well. (swimming, etc.)

# Story

  - Improve it, make it better. There used to be more here but I deleted it for fear of argument because apparently we all have to listen to one guy who&#39;s story has been… lackluster, at least compared to my ideas.

# Levels

**Normal Levels**

Update with the new graphics for their assets. Also: make them more interesting! Most levels are your run-of-the-mill left to right levels and don&#39;t make use of everything available, like most enemies, vertical space, varying directions, multiple paths, autoscrolling, signs, moving tilemaps, unisolids, bricks, multiple paths, those scripting bonus blocks that can be activated by rocks, etc. Make the most of the level gimmicks!

One of the most stupid and awful level design philosophies I have seen (especially considering it comes from one of the main level designers) is to water down the quality of certain levels to make others stand out, and to this I say: No! That is stupid! You&#39;re only going to improve with time, so you can always go back and add on more and more and make ultimately all levels better. And anyway, would you rather have two amazing levels of the same quality or one crappy level + one amazing level?

**Cutscene Levels**

Update these levels with the new story decisions and the new graphics/stuff decided for the characters.

**Boss Levels**

Update to accommodate the new fights and to make them a lot more interesting.

# Audio

**Tux, Penny, Nolok**

Add new sounds/cutscene speech. Perhaps use a new VA?

# Revamped Graphics

**Miscellaneous**

- Rusty Trampoline
- Switch Left, Switch Right, Switch Middle

**Backgrounds**

- Light Forest – add a few varying parallax BGs for normal light levels.

**Tiles/Decals**

- A multitude of new forest trees and tree branches to make the forest pretty.
- The tree moviestar exit.
- Revamp of the icy island tileset and icy bg tileset to live up to the new forest stuff.
- Miscellaneous other new tilesets for the forest/ghost forest to give it variety and a finished/varied feel

**Enemies**

- **Ghost Forest**
- Rotten Leaf/Ivy
- Rotten Tree/Leafless Tree
- Rotten Stumpy
- Ghost Tree Roots
- **Light Forest**
- Spring Leaf
- Autumn Leaf
- Tree
- Leafless Tree
- Stumpy
- Leafshot
- Zeekling
- Igel
- Snail
- **Icy Island**
- Bomb/Gold Bomb/Haywire/Shortfuse
- Crystallo
- Jumpy
- Snowman
- Bouncing Snowball
- Flying Snowball
- Snowshot

**Characters**

- Tux
  - Skidding
  - Swimming
  - Ducking
  - Backflip
  - Kicking
  - Dead
  - Worldmap Boat
  - Other/cutscene sprites…
- Penny
  - Other/cutscene sprites…
- Nolok
  - Other/cutscene sprites…
- Yeti
- Ghost Tree

# New Graphics

**Deeper Lava (tintable?) –** Suggested by mt and Daniel

**Acid –** Perhaps could be retinted lava.

**Waterfall -** Waterfall graphics matching the modern water style.

**New Icy Island Deco** – Perhaps look to Pingus for inspiration? The tileset should be as detailed as the forest, imo

# Important Bugs

- All worldmaps listed as new, regardless of if they&#39;ve actually been played or not.

# Features/Mechanics

**Swimming**

See feature/swimming for more info, it looks quite finished. However, some sprite improvements and overall tweaks are needed.

**Ghost Tree and Yeti**

Update boss fight/level/behavior to accommodate new ideas and graphics.

**Locked Doors and Keys**

Suggested by RustyBox, key would be like a powerup and would hovering over Tux and auto-unlock any locked door. Locked doors can&#39;t be opened, etc. Would be useful for puzzle stages.

**Tree Roots**

Ghost Tree&#39;s root attack roots should be used in earlier levels to foreshadow his coming. Suggested by RustyBox.

**Cod**

So Tux doesn&#39;t get lonely while swimming, a normal left-right fish enemy shall be added (equivalent of snowball in the water)

**Falling Acorn**

From Daniel; I&#39;ve had this idea for over a year, would be easy to implement, etc.

# Other, Unconfirmed Ideas

Only some, few or none of this stuff may be added, or might get added at a later time.

**Rocks activating pushbuttons**

This should definitely be added for puzzle stages.

**Rock throwing improvements**

Make rocks bounce off of Tux rather than killing him

**Music names**

The music should use a proper name instead of a filename when selecting it in the level editor.

**MULTIPLAYER**

First step, offline coop multiplayer, step 2 online multiplayer via Servers or a user code.

**Walljumping**

Could be quite useful and nice to have. Would extend move set of Tux.

**Sliding**

Due to current slope detection this might not get added, but it would be awesome to have Tux slide on his belly to hurt enemies and then fly off slopes after gaining momentum.

**Ice Cutlass**

A sword where Tux does a little dash. Might be available as a rock or as a powerup. If it is a powerup, it will replace the ice flower and its freezing ability.

**Picking up frozen enemies**

A very niche feature, especially if the ice cutlass powerup is added, but would be nice.

**Better frozen enemy graphics**

Every frozen enemy should have an overlay of an iceblock instead of unique frozen graphics for each, who look just plain ugly.

**3AM easter egg**

If the player plays Icy Island/other worlds between 3AM and 3:30AM, certain scripting events can happen. Levels get darker, scary, etc. easter eggs like &#39;bridge stuck&#39;

**After-a-while easter eggs**

Snowballs and other enemies do a little break after a while. After all, they were walking for so much time… Tux, after a while of not moving, also gets angry and curses the screen. Jumpy just. Stops jumping after a while

**Editor Improvements**

Autosave and a better text editor, open settings on creation of new level. Also improve infoblock UI (more like scripting UI)

**More velocity/acceleration driven platforms**

Allow platforms to be more velocity/acceleration driven, along with other objects that move (like Camera)

**Falling Platforms/Tilesets**

Set an option for platforms or tilemaps to function like icicles/icecrushers

**Treetop Tileset**

Tileset that takes place in large trees. Suggested by Grumbel, RustyBox, BlasterMaster, and Alzter

**Add support for rotatable/growing hitboxes**

Support for growing hitboxes should be added. Rotatable hitboxes might be a bit harder, though

**Controllable Platforms**

Two types: One where Tux holds UP to move it and one where Tux can move it freely. They should have sprites to separate them from others, though

**Sinking Platforms**

Platforms that sink when Tux is on them, and when he leaves, they go back up

**Movable climbables**

Climbables who move.

**Enemy Idea**

A walking enemy who quickly follows Tux and can&#39;t be killed, only stunned by stepping on it, but after reviving itself continues to follow Tux.

**Enemy Idea 2**

An enemy who copies exactly Tux&#39;s behavior and when catches up to him or collides with him Tux dies. Unkillable, but can be trapped as it only obeys Tux&#39;s moves and therefore how he collides as well. Basically a &quot;shadow-tux&quot; but would have a delay that the player can set.