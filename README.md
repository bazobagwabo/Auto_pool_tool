# Auto_pool_tool

		AutoPoolTool pixel version

- Put RBAssistSettings.ini inside your RBAssist folder
- Make a fresh turbohud installation and put 'gjuz' folder in the plugin folder (I don't reccomend using this thud for anything else than auto_pool_tool
- Right-click turbohud.exe and edit the AHK (you need to change the path to turbohud so AHK can launch thud as a failsafe)
- Start RBAssist
- Start Ros-Bot (MANUALLY)
- Start Auto_Pool.ahk in administrator mode
- start monitoring in RBAssist
- 
- This version will scan for > 9 pools, and then swap character. This is far more efficient than the other version.




		AutoPoolTool F6 version (simply pauses and resumes bot)

- Put RBAssistSettings.ini inside your RBAssist folder
- Start RBAssist
- Start Ros-Bot (MANUALLY)
- Start Auto_Pool.ahk
- start monitoring in RBAssist




		How it works

This tool will pool your characters through rifts while botting, swapping character every X rifts (changable in the AHK)
Start the tool with the character on top of your character list, it will go down your character list 1 by 1.
The tool will cycle through a maximum of 12 characters, then continue to do rifts on your last character indefenetely.

Make sure you have available stash space in the 4th stash slot (also changable in the AHK)

Make sure {space} is bound to clear all UI elements and 'k' + 'j' is not bound to anything in-game

Make sure you have saved the build you use for keys/rifts on the first armory tab on all characters

Run diablo in windowed mode, resized to smallest possible window (I only tested the AHK in 1080p desktop resolution, dont know if that matters).

If you can't figure out how this works, don't ask me.

have fun spending pools.


F6 version in action: https://www.youtube.com/watch?v=G9cry1QtmkE

		Changelog

v1.6
- Added pop-up window that asks you how many character swaps you want to do (the AHK will only change characters up to 11 times)
- Added instructions when launching AHK

v1.5
- Added pixel version that scans for pixel from turbohud (only shows when you have more than 9 pools)
- Read the AHK and you will understand, if not.. unlucky
- bugfixes

v1.4:
- Added easier way to edit how many character swaps the AHK will execute
- Added easier way to edit how many rifts you want to run per character

v1.2:
- Added failsafe for armory, it will force equip saved armory
- Added failsafe for adventure mode
- Edited some timings, longer sleep in menu

     
V1.1
- Fixed error in F6 AHK (it wouldn't resume after logging 3rd character)


