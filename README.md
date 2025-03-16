From Dust Hook-fix
=============

Hook for From Dust that enables the level editor, this forked version fixes the water simulation physics as well as adds a FPS config file.


# Instructions
1. Put fps_settings.txt into the root folder.
   Set your FPS in the file. Top number is FPS, bottom number is simulation rate. 
   I've found the best sim rate is your fps+5 (so 60 65, 120 125, etc).
   +1 may work fine too and will slow it down a very tiny bit, so you can try that too (60 61, 120 121, etc).
   A simrate lower than the FPS can cause the water to be a bit buggy.
2. Put XAPOFX1_5.dll in the root folder of From Dust, (same location as From_Dust.exe)
3. Put startup.txt into the root folder
3. Drag and drop BinPC in the root folder so it merges with the BinPC folder that already exists.
4. Go into BinPC/videoPatch and run videoSkipPatch.bat
5. Done!

Credit goes to  
https://github.com/DrChat/FromDustHook  
for creating the hook, level editor, etc.

Credit: an0nymooose  
https://steamcommunity.com/id/dilunn  
Implemented fps_settings, as well as the water physics fix after many grueling days staring at assembly.

Hints:

Yes the water will seem a bit faster, I think it's playable though as its not too much faster.
If you increase to 120fps+ it may feel too fast, but its up to you.

Any big brain reverse engineers out there, if you figure out how to slow the water simulation speed 
without it bugging and without lowering the fps, please add me on steam or comment on the thread in the steam forums.

# Editor Controls
```
1-4 - Scroll through the top menu bar (2/4 to swap layer/brush and 1/3 to go up/down on the shift menu
Ctrl - Smooth terrain inside the brush radius (on the selected layer)
1 - Copy (with copy and paste enabled in the settings)
3 - Paste (with copy and paste enabled in the settings)
Page up/down - Scroll through pages in the escape debug menu
Backspace? - Back out of a menu
Shift+tab - Scroll forward on pages in shift menu
F - Scroll back on pages in shift menu
MMB + mouse up/down - Tilt the editor camera (this continues on its own though so you have to go in the opposite direction to stop it)
Left/Right click ?- Zoom in/out
Q/E - Rotate the camera
```
