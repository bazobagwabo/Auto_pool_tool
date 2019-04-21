# Auto_pool_tool
automatically pools up your characters through rifts, at the moment set up to pool up 12 characters (can edit this in the AHK).

		AutoPoolTool F7 version

- Put RBAssistSettings.ini inside your RBAssist folder
- Start RBAssist
- Start Ros-Bot (MANUALLY)
- Start Auto_Pool.ahk in administrator mode
- while Ros-Bot is active press ctrl-o
- start monitoring in RBAssist




		AutoPoolTool F6 version

- Put RBAssistSettings.ini inside your RBAssist folder
- Start RBAssist
- Start Ros-Bot (MANUALLY)
- Start Auto_Pool.ahk
- start monitoring in RBAssist



		How it works

Tool will pool your characters through rifts while botting, swapping character every 15 rifts (changable in the AHK)
Start the tool with the character on top of your character list, it will go down your character list 1 by 1.
The tool will cycle through 12 characters, then continue to do pools on your 12th character indefenetely.

Make sure you have available stash space in the 4th stash slot (also changable in the AHK)

Make sure you have saved the build you use for on the first armory tab on all characters (also changable in the AHK)

Make sure your skills are set up the same way on the action bar if you're using the F6 version

Run diablo in windowed mode, resized to smallest possible window (I only tested the AHK in 1080p desktop resolution, dont know if that matters).

If you can't figure out how this works, don't ask me.

have fun spending pools.

https://www.youtube.com/embed/G9cry1QtmkE

		Changelog

V1.2 - Added failsafe for adventure mode (in case account gets reset to campaign mode)
     - Added failsafe for armory, it will force equip even if some gems or gear is missing
       (better to do shitty runs, than to not do runs at all)
     - changed some timings when changing character, longer sleep timers in mennu
     
V1.1 - Fixed error in F6 AHK (it wouldn't resume after logging 3rd character)

