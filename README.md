# Auto_pool_tool

		AutoPoolTool F7 version (REMOVED AS OF v1.5)

- Put RBAssistSettings.ini inside your RBAssist folder
- Start RBAssist
- Start Ros-Bot (MANUALLY)
- Start Auto_Pool.ahk in administrator mode
- while Ros-Bot is active press ctrl-o and make sure 'Start botting !' button is highlighted
- start monitoring in RBAssist




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

Make sure {space} is bound to clear all UI elements and 'k' and 'j' is not bound to anything in-game

Make sure you have saved the build you use for keys/rifts on the first armory tab on all characters

Run diablo in windowed mode, resized to smallest possible window (I only tested the AHK in 1080p desktop resolution, dont know if that matters).

If you can't figure out how this works, don't ask me.

have fun spending pools.


F6 version in action: https://www.youtube.com/watch?v=G9cry1QtmkE

		Changelog
v1.5
- Added pixel version that scans for pixel from turbohud (only shows when you have more than 9 pools)
- Read the AHK and you will understand, if not.. unlucky

v1.4:
- Added easier way to edit how many character swaps the AHK will execute
- Added easier way to edit how many rifts you want to run per character

v1.2:
- Added failsafe for armory, it will force equip saved armory
- Added failsafe for adventure mode
- Edited some timings, longer sleep in menu

     
V1.1
- Fixed error in F6 AHK (it wouldn't resume after logging 3rd character)


