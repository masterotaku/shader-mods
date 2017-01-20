RE1 real time graphics mod (hotkeys for noise filter, color filter, etc)

If you thought crushed blacks in backgrounds were impossible to fix, you were wrong. This mod, made thanks to the Helixmod dll, allowed me to dump and modify shaders responsible for effects that deserve to be in an options menu (for RE0, go here: https://steamcommunity.com/app/339340/discussions/0/343785574521847386/ ).

Place the files in the root folder of the game, "Resident Evil Biohazard HD REMASTER".

If you use the fps fix mod, which is also a "d3d9.dll", rename it to something else and uncomment the ProxyLib = "I:\Steam\steamapps\common\Resident Evil Biohazard HD REMASTER\fpsfix.dll" line in "DX9Settings.ini", writing the correct path to the renamed dll.

Hotkeys (by default all effects are untouched):

- F1: noise filter toggle.
- F2: black crush / color filter toggle.
- F3: fog toggle. You should toggle back to the default setting for ingame cutscenes, or else there will be a broken depth of field effect.
- F4: bloom toggle (effect not present in many places). It also disables the map and menu graphics, so if you want to try it, make sure it's only when you're controlling your character.

There is a "profiles" folder I made with two different "DX9Settings.ini". One of them is the default one, and the other has the noise filter, color filter and fog disabled by default.

In RE1, background textures have noise themselves, due to the scaling process Capcom made.

Some of the effects are made to compensate each other's brightness and contrast, so sometimes disabling just one effect won't be a good idea. I recommend disabling noise, color and fog in general, and only enable fog when needed.

With those F1 to F3 effects disabled, the character lighting sometimes doesn't seem to blend with the background as perfectly as before. But seeing all the backgrounds detail is worth it.


Example screenshots:

Default: http://u.cubeupload.com/masterotaku/bhd20160903215420319.png
No noise, no color, no fog: http://u.cubeupload.com/masterotaku/bhd20160903215417293.png

There are probably better examples than this one, but look at the right wall and the stairs.