# Unlisted Objects in Editor

Adds several unlisted objects to the appropriate tabs in the level editor. Massive thanks to NicknameGG for the tutorial on adding objects to new editor tabs, as shown here: https://github.com/NicknameGG/The-intense-adding-of-a-new-object-in-a-new-tab. If you know of other unlisted objects that you want in the mod, or if there is a bug that needs fixed, let me know at https://github.com/angelotrabuco2013/Geometry-Dash-Unlisted-Objects-in-Editor.

If, for some reason, you want to enable unstable objects, paste this at the bottom of mod.json: 
		, "removeUnstable":{
			"name": "Remove unstable blocks",
			"description": "Removes blocks that are likely to cause the game to crash. I do not reccomended turning this off",
			"type": "bool",
			"default": true
		}
, enable the commented lines of code 42, and 52-54 in main.cpp, and comment out or remove line 43. This is nearly guarenteed to cause the game to crash when entering the level editor. 