# UnlistedObjectsinEditor

If, for some reason, you want to enable unstable objects, paste this at the bottom of mod.json: 
		, "removeUnstable":{
			"name": "Remove unstable blocks",
			"description": "Removes blocks that are likely to cause the game to crash. I do not reccomended turning this off",
			"type": "bool",
			"default": true
		}
, enable the commented lines of code 25, and 35-37 in main.cpp, and comment out or remove line 26. This is nearly guarenteed to cause the game to crash when entering the level editor. 