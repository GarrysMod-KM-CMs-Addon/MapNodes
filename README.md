All kinds of nodes and polished navmeshes for Garry's Mod maps, made for KM_CM's Addon.

Saved in folders in format "[MapName] [Version]". Note that if versions are different, it might not work.

You can check your map's name and version by running `lua_run print( game.GetMap() .." " .. game.GetMapVersion() )` in the console as a superadmin.
Example output: `gm_construct 1765`

# How to install

This is NOT your typical Garry's Mod addon! You have to manually put `.nav` files in `/garrysmod/maps`,
and `.json` files in `/garrysmod/data/covers/` (create folders if don't exist). Don't forget to backup
the original nav files, or some consequences might happen... I have no idea to be honest.

If you really feel like installing the cover nodes onto a different version of the map,
just change the last digits to the output of `game.GetMapVersion()`. But note that they may break.
