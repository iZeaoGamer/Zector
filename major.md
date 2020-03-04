## V11.0; MAJOR

# Note:
# We have made a lot of changes over the new v11.0 update, which fixes bugs, and implements a new server coming soon.


As a part of the v11 update for the network, we may be adding Classic OP Factions. Classic OP Factions is factions, but more classical. Basically, a 2017 style. 2017 in which made void factions popular. (40-60 players online).
Through out the upcoming updates, we’ll be attempting to reimplement the biggest and most oldest features back in 2017. Or atleast the features we introduced to VoidFactions 2017. Before seasons, before scoreboards, and using the old API 1.12.0. Along with this, we’ve also introduced a custom version of the server software. No, we never made it, but re-adding the most vanilla-features, and reimplementing our own systems from before, rather than re-creating plugins for this,
- Add basic implementations for Ender pearls. (Currently doesn’t work. Will try to fix this soon.)
- Added the good ol days factions plugin.
- Add basic implementations for Elytras - Yes, they do currently work. Fly like a plane!
- Fixed crashes upon leaving the game.
- We’ve introduced support for wider-range MC versions, starting from v1.2 to the latest versions of minecraft. Along with this, we may also support beta versions too!
- Added back /seen, works better than ever!
- Added sign shops - Unfinished.
- Fixed errors when typing /f help
- Fixed errors onEnable()
- Fixed errors upon join.
- Fixed enderpearls.
- Fixed duplication glitches with enderpearls, because it wasn't fully complete as of that time.
- Using /heal and /feed will give you the "hearts" particle once healed, just like back in the 2017 days!
- Implemented Ender pearl cooldown, just like vanilla! (Currently in BETA)
- Chatting in-game is now fixed, time to start chat formatting. ;p
- Fixed crash upon breaking.
- Basic implementation for Vanilla-like Mob spawners.
- Added /spawner - Allows you to buy spawners, the old fashioned way!
- Added /spawner list - To see a list of availble spawners.
- /spawner <mob> will now give you a mob spawner with the mob inside of the cage, and is now placeable, just like vanilla! Yes, it costs economy to buy the spawners.
- Fixed a bug, where spawners wouldn't function correctly, making it non functional tile.
- Some mobs now have an AI built in to the software.
- Added protocol support for MC version: v1.15.0.54 BETA Build. (Untested)
- Added new event; EntityGenerateEvent, which executes the Generation of Entities from spawners.
- Basic Implementation for Spawn eggs.
- Fixed errors in console which caused mobs not to spawn properly.
- Fixed ender pearls from players being able to collide themselves. (Tested to be fixed.)
- Added Ender and nether worlds, they look a lot like vanilla now. yay!
- We're now using a vanilla-like server software instead of using the older versions of its API. Yes, this does mean we won't be supporting multi-versions or even beta versions. This however, may come in the future.
- When teleporting to the end or nether, it'll now say "Building terrain" just like vanilla!
- Implemented better normal world generations.
- Re-coded /spawner command completely due to the older-type API that previously supported this.
- Added implementations for Hoppers.
- Added implementations for EnderChests.
- EnderChests can now open properly.
- Add basic implementation for ShulkerBoxes.
- Fixed players not being able to join properly due to chunk problems.
- Fixed chunks taking forever to load even if you have fast internet. This problem only occurred here because of how chunks generated.
- Added a lot of new blocks that are in vanilla.
