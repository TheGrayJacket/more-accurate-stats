# more-accurate-stats
An ExileMod override that replaces flat armor sum being displayed on Vests and Helmets with a more accurate damage reduction stats from projectiles and explosions.

# installation:

Download and drop the override file to a 'folder-of-your-choice'

Add following like in your missionconfigfile > config.cpp > CfgExileCustomCode :

ExileClient_util_item_getMainStats = 										"'folder-of-your-choice'\ExileClient_util_item_getMainStats.sqf";

