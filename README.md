# csgo-enhanced-bots
Tweaked botprofile.db file for Counter-Strike: Global Offensive to make bots much more difficult.
Expert bots in CS:GO can be still too easy to play against, so this new bot profile tweaks the bot's aim and reaction time to make them faster and provide better practice.

## Features
 - Faster reaction times and better vision
 - Tweaked weapon buy profiles, removing unpopular weapons like shotguns (rifle bots will mainly buy AK/M4, sniper bots will mainly buy AWP/Scout)
 - Bots modeled after recent professional team rosters, with each player having stats roughly matching their skill
 
 ## Instructions
 - Simply replace your existing botprofile.db file (located in ...\Steam\steamapps\common\Counter-Strike Global Offensive\csgo) and ensure Expert bots are selected in-game, since any bots below Expert have not been modified.
 
 ## Notes
 - The Sniper and SniperPro buy profiles are very similar, but the Sniper profile will buy a rifle (AK/M4) first, and then an AWP when the bot can afford it. The SniperPro profile will make the bot buy a Scout until it can afford an AWP.
 - I highly recommend pairing this with [some improved map navmeshes](https://github.com/manicogaming/NavMeshes) that can help with the bots' decision making and removes some spots where bots can get stuck on some maps.
