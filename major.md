## V11.0; MAJOR

# Note:
# We have made a lot of changes over the new v11.0 update, which fixes bugs, and implements a new server coming soon.


As a part of the v11 update for the network, we may be adding Classic OP Factions. Classic OP Factions is factions, but more classical. Basically, a 2017 style. 2017 in which made void factions popular. (40-60 players online).
Through out the upcoming updates, we’ll be attempting to reimplement the biggest and most oldest features back in 2017. Or atleast the features we introduced to VoidFactions 2017. Before seasons, before scoreboards, and using the old API 1.12.0. Along with this, we’ve also introduced a custom version of the server software. No, we never made it, but re-adding the most vanilla-features, and reimplementing our own systems from before, rather than re-creating plugins for this,
- Add basic implementations for Ender pearls. (Currently doesn’t work. Will try to fix this soon.)
- Added the good ol days factions plugin.
- Add basic implementations for Elytras - Yes, they do currently work. Fly like a plane!
- Fixed crashes upon leaving the game.
- Added back /seen, works better than ever!
- Added sign shops - Unfinished.
- Fixed errors when typing /f help
- Fixed errors onEnable()
- Fixed errors upon join.
- Fixed enderpearls.
- Fixed duplication glitches with enderpearls, because it wasn't fully complete as of that time.
- Using /heal and /feed will give you particles once healed and fed, just like back in the 2017 days!
- Implemented Ender pearl cooldown, just like vanilla! (Currently in BETA)
- Chatting in-game is now fixed, time to start chat formatting. ;p
- Fixed crash upon breaking.
- Basic implementation for Vanilla-like Mob spawners.
- Added /spawner - Allows you to buy spawners, the old fashioned way!
- Added /spawner list - To see a list of availble spawners.
- /spawner <mob> will now give you a mob spawner with the mob inside of the cage, and is now placeable, just like vanilla! Yes, it costs economy to buy the spawners.
- Fixed a bug, where spawners wouldn't function correctly, making it non functional tile.
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
- Fixed players being able to kick themselves from the faction.
- Fixed players being able to promote themselves from the faction.
- Fixed players being able to demote themselves from the faction.
- Fixed players being able to transfer leadership to themselves from the faction.
- Fixed players being able to invite themselves to their own faction.
- Fixed /seen from causing errors.
- Added a check to ensure whether or not the player's been seen before in /seen.
- Fixed /seen for its latest API's of the plugin.
- Added back /feed and /heal, re-added some awesome particles to go along with it.
- Added first played section to /seen, so you can now check when the player first started playing the server.
- Fixed internal server errors upon player join.
- Re-added back /spawner, made it even better.
- Added a new way of confirming your purchase with spawners. Simple steps here:
Type /spawner <spawner/list> <count>. If count is empty, it'll recognize it as 1. Once you've done that, it'll ask you if you're sure you want to preceed this purchase along with the purchase information. All you need to do, is type into chat "yes" or "confirm" to finish the purchase. You can however, cancel the purchase by typing "no" or "cancel" to cancel purchases made previously.
- Mobs can now be activated whether if it is day or night. Before, this wasn't possible.
- Added new functions: setArgs() and getArgs() to spawners shop.
  
setArgs(): Sets the args the player is selecting (Basically its information nobody needs to see lol).

getArgs(): get's the full arguments of a player. Returns empty if player data not found.
- Added timed ranks, just like on void, back in 2017!
- Added some new timed ranks, staff and donator ranks now have bypass to the plugin to prevent issues to do with the plugin setting other player's ranks to a lower rank.
- Added PureChat, and PurePerms back!
- Fixed chat formatting.
- Add a new /wild plugin.
- /wild no longer brings you to the air.
- /wild now has a re-coded timer before teleportation.
- Add basic implementations for portal generations to the nether. (In BETA).
There are some bugs with this such as:
Building terrain not disappearing when teleporting between dimensions.

- Entering the nether portal should now teleport you faster than before. (Atleast 1 second after entering before teleportation. Before, this would happen 4 seconds after).
- Added implementations for Enchantment tables.
- Add basic implementations for end portal generations. (Currently in BETA, and may not work as expected).
- Added hud (Popup), just like back in 2017, before scoreboards.
- Added a check to ensure whether or not the player is in a faction for the hud. If not in a faction, it’ll return with the message: “No faction” instead of returning blank.
- Fixed nether portals from crashing the server.
- Fixed nether portals from lagging the server.
- Fixed coordinates from returning a different color for Y and Z instead of leaving it as the same color.
- Added drop party (Unfinished)
- Added Chat Scramber, implemented new words to the chat scrambler system.
- Fixed a crash upon player join.
- Fixed a bug, where the hud bar wouldn’t appear even if the player had joined. You’d need to use the check to ensure whether or not the player should be having the hud bar.
- Add basic implementations for Ender eyes. (A.K.A Eye of ender)
- Fixed Eye Of Ender from having unusual behavior.
- Fixed Eye Of Ender from not being placeable to the end portal frames, making it impossible to create the end portal.
- Fixed a bug, where building terrain wouldn’t disappear. Note that most of this has been fixed. However, you may still experience this from time to time, since this is a Minecraft glitch. But we’ve patched some issues raised to do with this issue always occurring.
- Fixed missing dollar symbol ($) from hud.
- Added Online: counter section to the super hud.
- Fixed cpu leak related to entity movements (~%550)
- Optimized Entity updates (increases server tps adds delay to other world entities.
- Added SkinAdapter things for api usage
- Fixed Hopper transaction issue

### Combat Logger Updates
- Better formatting for plugin.yml
Implement functional Creative mode checks.
- Rename CreativeCheck() to hasCreativeCheck() for better quality codes. [1 / 2]
- Creative checks no longer depend on the server’s check. It will now require a Player dependency, rather than implementing it to the server, making the plugin non functional. This changes:
1. Parameters for setCreativeCheck(), add’s Player parameter checks.
2. Parameters for hasCreativeCheck(), add’s Player parameter checks.
3. Changed CreativeCheck[] formatted arrays to require player name, instead of being kept false or true without requiring player’s name input.
4. Added onJoin() class event to prevent any future errors with hasCreativeCheck() not being recognised as false or true.
- Reformatted the code to make it look better.
- Fixed Syntax error
- Rename use import from PlayerJoinEvent to PlayerLoginEvent - This is to prevent undefined index issues. (Server crashes upon join) because before, the task was being executed first before the onJoin() event. The onJoin() event allows the creative mode checks to be set to false so the plugin actually recognises a true / false phase.
- Added $player->spawned function to The hud task. This check is to ensure the player must be spawned in before executing the task. The task can’t go first before the onJoin() event. Otherwise, there will be errors.

### OTHER UPDATES
- Added awesome nametags above your head.

### NOTE
## The combat logger update will be pushed to the rest of the servers soon.
## Also note we’ll be removing the flight disabled upon Damage event, and instead, allow checks to be made within the combat timer plugin, making it a lot easier to handle, and less issues too. Also, less bypasses within the plugin.
