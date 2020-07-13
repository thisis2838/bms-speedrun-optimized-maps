## About
 Black Mesa's maps optimized for speedrunning!
 
 This project aims to modify the maps of Black Mesa to remove cutscenes and annoying, skipped or time-wasteful sections in the speedrun route, creating a more fun speedrunning experience.
 
 Get the compiled maps [here](https://drive.google.com/drive/folders/18-N0WWyPNHEfCk-AfjsnewXKahpjBKr_?usp=sharing).
 
 Please if you find a bug report them in the Issues tab.
 
## Installation
 1. Download the maps from the link above, then move all the .bsp files into `your Black Mesa root folder > bms > maps`. 
 2. Open up `gameinfo.txt` in the `bms` folder and look for a line that says `game+mod bms/bms_maps.vpk`, add `//` in front of that line.
 3. Run the game and all the maps should be replaced!
 
 If you wish to disable the mod and return to the old maps simply revert what we did in step 2.
 
## Details
 These maps are modified from the 0.91 version of Black Mesa; however, due to technical issues with the decompiled maps some of them have entities from 0.91 and brushes from the [2017 Source Engine Security Fix update](https://steamcommunity.com/games/362890/announcements/detail/1435939287373772097), which is the very last version where the developers officially released .vmfs. As such unmodified parts of the maps might not exactly resemble the original.
 
## Todos
 As said from before, these maps are imperfect and will need cleanup so that they could more match the originals. At this point in development, this project will need:
 1. Recompiling at Final quality for better lighting.
 2. Build and fix cubemaps.
 3. Checks and fixes for bad I/O connections and info_overlays for maps that needed to be combined with their 2017 counterparts.
 4. Playtesting to flush out bugs and give suggestions on what else to cut or what to change.
 
If you are interested in helping feel free to aid in shortening this list!

## Credits!
 Table, the_kovic and XCape for guide on where and what to cut out. 
 
 [The Black Mesa Speedrunning Community](https://discord.gg/pZ8TZ9w) for support and making this possible!
 
 Special thanks to:
 - Imperfect decompiling for making life 70000 times harder.
 - The Devs for making me do this:
 
 ![Chris Horn, lead dev on the old Questionable Ethics skip, one of the biggest in the run now patched](https://i.imgur.com/GpXWe89.png)
