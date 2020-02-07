## CHANGELOGS

## V9.0; UPDATE THAT CHANGES EVERYTHING

- Added a complete revamp to Custom enchants.
- Fixed Wither skull enchantment (remains) not disappearing when thrown.
- Fixed Porkified enchantment (remains) not disappearing when thrown.
- Parachute now uses negative Levitation effect to simulate slow falling.
- Custom enchantments are now registered into PocketMine-MP.
- Fixed issue where throwing a projectile and switching to a different weapon would trigger the custom enchants of that weapon. 
- Fixed "WitherSkull Enchant does not apply Wither Effect."
- Added new Custom Enchant: Deep Wounds. Description: Inflict on enemies deep wounds that cause bleeding.
- Added new Custom enchant: Bombardment. Desc: Bombard enemies with TNT when shot.
- Added new Custom enchant: Homing. Desc: Arrow will home in on the nearest entity.
- Revamped Mob stacking completely! Introduced Built-in Mob spawner stacking + Mobs stacking all in one plugin.
- Added Coin Flip.
- Improved the mob stacking UI a ton.
- Fixed looting for Villagers
- Fixed looting for Zombies.
- Fixed Looting for Witches..
- Sponges now obsorbs water, just like vanilla. yey!
- Beacons should now function just like vanilla, yey.
- Fixed internal server errors when killing zombies.
- Villagers now drop Diamonds, and Witches now drop Emeralds without the need of the custom mob drops plugin.
- Added a new enchantment UI system - Should work with vanilla enchantments.
- Fixed /gmc from giving you internal server errors.
- Fixed /gms from kicking you due to internal server errors.
- Fixed Spectator mode from kicking you due to internal server errors.
- Recoded looting enchantment to work better with all lootable mobs.
- Fixed an issue, where looting wouldn't be like normal Looting in vanilla. Before, the mob drops would add onto the loot enchantment depending on its levels. Now, it will multiply depending on the amount of looting enchantment level. This is vanilla behavior, and will stay like that.
- Fixed internal server errors when killing a Snow Golem.
- Most mobs should now drop appropriately depending on the amount of loot enchantment levels, and if the player has an looting enchantment in their hand when killing a mob.
- Re-added $lootingL from 0 to 1. This change was made because if the player didn't have a looting enchant, they wouldn't get any mob drops. Should be fixed now.
- Fixed Mob Stacking UI from not displaying properly. 
- Fixed random server crashes with Mobs.
- Added Faction value. How this works:
You can place spawners, which will boost up your faction value by 100.
- Added /f top worth and /f top value.
- When you break a spawner, it'll now take away your faction value by 100 per break.
- Fixed a bug, where your faction money would turn into negative amounts. This was never a good idea because it wouldn't be fair on the player killed. It should really stay at zero, and not into negatives. We don't like negative numbers now do we? ;P
- Added /f seeworth.
- Added /f worth.
- Added, and completely recoded administration commands - It no longer requires operator to execute admin commands. It will now rely on permissions.
- Removed /f rename for now. Will implement this back very soon with some fixes.
- Added back /f rename finally with a few bug fixes!
- Fixed New faction name field overwriting other faction names.
- Changed Already existing faction message.
- Added Faction already existence by somebody else message.
- Faction values will now transfer to the renamed faction.
- Faction value specifics will now delete if the specific faction name no longer exists. (Deleted, gone.)
- Fixed /f admin addstrength errors once executed.
- Fixed /f admin addstrength messages from showing the wrong information.
- Added bosses finally! Yay!
**NOTE**
Bosses are currently in BETA, and there is only one boss at the moment. We plan to add more bosses in the future.
- Added Auto spawner stacking BETA - How this works: When you place two spawners of the same type nearby, it will automatically stack.
- Added /combiner. How this works? It works just like an anvil, but instead, it provides: Custom enchants support, and UI support also. No need for anvils anymore, this is definately 10x better, and items with custom enchantments on them will no longer disappear, due to this new feature. We may however, depreciate anvils, and just implement /combiner support.
- We've done a full playervaults update, which includes a lot of bug fixes, and features being added.
- Added permissioning groups - So instead of giving players playervaults.vault.2, playervaults.vault.3, we can just give them the name of the vault (as pre-made by me). For example, playervaults.vault.coal, which will provide them the appropriate amount of playervaults, instead of the fucked up permissions system with playervaults which got too confusing.
- All ranks should now have the appropriate amount of playervaults.
- Unfortunately, we have removed staff ranks being able to use /pv 2 or more. This is for two reasons infact.
1. Because if someone were to get demoted, then they'd no longer have their previous playervaults. And this would just get hella confusing.
2. Because in a way, it is simply what we'd call "Abuse". This is what we call "Apply to get ranked permissions". Not as in /ban, but as in using donator, or youtube permissions. This will be explained in an announcement shortly.
- Fixed a bug, where some players wouldn't be able to open their Playervaults. As soon as they would open it, it'd instantly close again.
- Bug fixes with Mob spawner stacking - Still more to fix soon.
- Removed timer display for Mob spawning due to confusion issues.
So in this update, we've completely revamped permissions, groups, and how they're handled. Starting with:
- Implementation for multi-server support - Yes, we've finally added a mySQL database for our Permissions system. This also means you will no longer have to go through all servers just to set someone's rank! It's as easy as 123.
Want to set it on all servers at once? Great! Same command, it will be accepted as one command. This means you can set someone's rank, say on Factions, and it'll transfer to all of our servers from the network. At the moment, there's no particular use for this. This will be introduced on OP Factions S9, and OP Prisons S5.
- We have also moved to a new host for OP Factions S9; At the moment, the groups aren't linked between servers. This will be introduced in the new seasons of the gamemodes. The hub is however, linked as of right now, and is also linked to OP Factions S9. However, there is no backwards compatibility between previous seasons. This means linking won't work on S8 of OP Factions and below. This is just a new feature introduced in S9, which will make databases more useful, since we'd have multiserver support by then.
This new system will also be 10x easier for us managers and owners when setting player's ranks on the servers.
- Fixed floatingtext from lagging the server.
- Added floating text factions top! Including its rewards!
- Added a new trading system - It should be a lot better than the old system with improvements to the plugin. We may/may not depreciate the clicking the player to trade system. This is still yet unknown.
- Fix small TPS lag.
- Revamped the shop UI!
- Fixed all shop images in this season! yey!
- Added new categories, thanks to Scrt! Fixed by me.
- Added spawners compatibility with shop UI (Working spawners! ;D)
- You can now buy working spawners from the shop finally! ;D
- You can now sell certain things in /shop. /sell may be removed this season.
- Revamped messages, made in /shop! Made them so much more cleaner, and it now makes sense.
- Fixed the random $ sign being there when it shouldn't be, since it was counting the amount of that item, not the amount of money. (After clicking a category that is)
- Messages are now made in english (lol, god knows who wrote that before).
- Fixed internal server errors when selling items in /shop.
- Removed slider, and just implemented amount field via input field. That way, players have more control over how much they want to sell.
- Added a new auctionhouse system - Better than ever.
- Fixed all of the inventory being buggy issues.

## What was the bug?
There was a major bug back on MC 1.12, where inventory on servers would be buggy. Causing cursor inventory to not clear client side this means those that were cancelling item movement from inventories events would get bugged. Now, the thing would happen, is the items that aren’t moveable, would sometimes still be moveable, and sometimes would dissapear. The thing that should happen: It should instantly come back to the inventory that was there previously, rather than moving and get’s buggy.

## The real meaning
So there are events with pocketmine. Events that do different actions, or even create your own events. Yes, this is in a coding term.
There is an event called InventoryMoveItem (relating to that name), which you can cancel that event, allowing it to not execute that event. In this case, cancelling the event would make it so players aren’t able to move items out of a specific inventory.
Now, there is certain plugins that have this to prevent any cheating or exploits.
The bug was - When they cancel the Moving items from inventory event, this would cause to bug out, or worse - Sometimes not work.
This would then lead to items being able to come out of the said inventory, into a player’s inventory. Sometimes it’d stay there, sometimes it’d go after a bit.
Basically, the items that were in the previous inventory are client sided issues. This means items that are being pulled out of an event cancelled inventory, aren’t really there for the rest of the players. They’re simply there for the specific player. This is a client sided issue, which we managed to patch for our servers.
So you should no longer reoccurr issues to do with inventories and its client sided issue.


- Fixed /f top value, and /f top money from showing the wrong rank number.
- Fixed koth set up commands from not working. Such as: /koth p1, /koth p2, etc.
- Fixed koth teleportation not working when using /koth join.
- Koth will now randomly teleport you to a specific spawn point in the arena when using /koth join - Yay, finally fixed.
- Fixed server crashes when teleporting to koth arena.
- Fixed getting kicked for internal server errors when teleporting to koth arena.
- Added /tags - Allows you to choose a tag!
- Added, and re-coded crates system! Includes:
- Fixes to floating texts duplicating each other.
- Added Tags crate - Allows you to unlock tags for free!
- Added Legendary crate - Revamped too.
- Added epic crate - Revamped too.
- Added new crate: Ultra.
- Added vote crate - Revamped too.
- Added Mythical crate - Revamped too.
- You can now gain crate keys when mining.
- Prevented players gaining keys in protected areas.
- Factions compatibility added to crates. This means you can get faction power from crates.
- Fixed /tags permission from becoming broken.
- Added /bin - Allows you to delete your items that you don’t want.
- When killing a player, and Breaking blocks, XP will now go directly to your inventory, eather than dropping it.
- Removed crafting.
- Updated java edition blocks to MCPE Blocks.

## Koth MAJOR RECODE + REVAMP
- Change how player classes generate.
- A lot of configurable features you can play around with.
- Koth 3.0.0 brings in so many bug fixes, and new features added.
- You can leave koth arenas! By typing /koth leave
- Fixed teleportation bugs when using /koth join (An issue on 2.0.0)
- Renamed /koth p1 to /koth pos1
- Renamed /koth p2 to /koth pos2
- Added Player help commands! Type /koth or /koth help to display those! (Will also include new administrative commands if the sender is opped.
- Game timer is now editable in-game! Type /koth setgametime
- Added event timer - Will now automatically broadcast whenever a koth event is about to start.
- Event Timer is now editable in-game! Type /koth seteventtime
- Event timers + Game-timers can now be translated to seconds/ticks. You can type /koth seteventtime , which will allow you to edit the event timer (By auto, not manual).
- Add FactionsPro Support
- Add Discord Support
- Fixed koth teleportation from not teleporting them to exactly the correct world.
- Fixed /koth setgametime from not updating properly.
- Fixed /koth seteventtime from not updating.
- Add KothPlayer class, where it'll store all of the player data. At the moment, it only supports isInGame(), and setInGame(bool). We may add more to this in the future.
- Fixed a bug with koth, where when the game ends, you'd have to log off and log back on to use some commands again. (This was an issue from previous seasons).
- When the koth game ends, it'll no longer broadcast player quits in #koth chat. This is due to confusions with whether the game actually ended or not.
- Made Koth rewards even better! + Also implemented configurable koth rewards for server owners!
- Protected Spawn, Warzone, and Koth Arena properly.
- Added back Money Pouches, but with a recode behind the scenes. ;D + Money pouches has now been coded in differently than previously to make it more stabled.
- Koth event is now every 12 hours, instead of every 2 hours. This is because 2 hours is simply way too short for a proper koth game.
- Added crates to spawn.
- Fixed koth spawnpoints - They're now separated apart so there's less spawn killing going on in the koth arena if someone dies.
- Allow FactionsPro to be optional support, not required support. (For server owners).
- /koth start can no longer be duplicated. - This would be due to there not being a started = true function, which detects the game has started.
- Fixed /koth stop from being able to be stopped more than once.
- Fixed /koth stop from sometimes saying "Koth game already stopped", even though, the game's still classed as "started".
- Fixed internal server errors upon player join. This would be due to worldguard only allowing interger, not float. (As in 1.0). That's a float. And 2 is a integer.
- Fixed worldguard regions not updating unless you moved. This included: PvP Bypass. For example, if you were in a unprotected area, stood still, and typed /spawn, you'd still be able to hit that person until he moves. All fixed now. ;D
- /f claim protection is more better, and easier than ever!
- Players are now unable to type /f claim if they're inside a region.
- Regions for players are now updated automatically, instead of when you move. This was a major issue back on previous seasons when this issue did occur.
- Players are no longer able to place spawn eggs inside of regions. (If allow-mob-spawning flag is set to deny.)
- Fixed regions database from resetting.
- Fixed Gen buckets! They no longer bug out finally!
- Fixed /gbuy from displaying the entire item info, and not just the item name.
- Gen Buckets should no longer be spammed even if you only clicked once.
- Does anyone remember this? (Screenshot) Well, this was the CE Shop we used to use awhile ago. You could basically get some CE books that came with randomised custom enchantment books. Well, it's now back, better than ever, wth a few more new Custom enchants added.
- Fixed a bug with /ceshop, where on the confirm page, even if you clicked "No", it'd still allow you to buy the ce books. This would've been a major issue if I didn't patch this. Since there would be no way of exiting out of the UI.
- Sand, and Obsidian gen buckets have been newly rebuilt, to support some Bucket types, instead of having a empty bucket, which apparently was the cause of it not working properly.
- Added NPC's at spawn.
- Fixed /mban from not working correctly.
- Fixed a bug with /mban, where when exiting out of the Bans control after clicking the player name in /mban, or when you type /mban <player>, it'd come up with an error message, which wasn't correct because you only exited out of the bans control UI system.
- Complete Mute UI-Recode - It's similar to /mban, but with /mmute.
- Complete code clean-up for MultiMuteUI, allowed Mute UI to only allow one text message of code per ban, not multiple per reason. This before would've flooded the chat, so we had to implement this.
- Fixed internal server errors when using /mmute.
- Mutes will now add up the mute durations per reason properly. 
- Changed some Mute reasons, added a few more new reasons to the Temp mute UI.
- Added Silent Mute to TempMutes!
- Fixed players not being able to execute certain commands even if it's not a way to bypass the chat.
- Complete re-code to players not being able to use certain commands. Yes, this is now fixed in S9 of OP Factions.
- Fixed a bug, where in Mute control panel UI, it'd say a message even if you exited out of the Mute Control Panel UI.
- New button; Exit - In the Temp Mute Control Panel UI, where you can exit that way as well.
- Fixed internal server errors when executing commands.
- Fixed /mmute sometimes not muting the actual player.
- Complete Mute UI-Recode - It's similar to /mban, but with /mmute.
- Complete code clean-up for MultiMuteUI, allowed Mute UI to only allow one text message of code per ban, not multiple per reason. This before would've flooded the chat, so we had to implement this.
- Fixed internal server errors when using /mmute.
- Mutes will now add up the mute durations per reason properly. 
- Changed some Mute reasons, added a few more new reasons to the Temp mute UI.
- Added Silent Mute to TempMutes!
- Added a new check to ensure whether the player is banned or not before executing /mban command with tempbans.
- Added a new check to ensure whether the player is muted or not before executing /mmute command with tempmutes.
- Enabled a check to ensure the player isn't muting themselves.
- /afk no longer puts you in god mode. (Was easily abused in many ways.)
- You can no longer hit other players whilst in vanish. (Untested)
- You can no longer get attacked whilst in vanish. (Untested)
- You can now teleport to vanished players using our new vanish plugin. (If you have permission to see other players whilst in vanish.)
- Removed /vanished plugin until further notice - This will then help us in the future to support this compatibility using our newer vanishing system.
- Flight will no longer disable when you hit a player if you're in vanish. (Untested)
- Flight will no longer disable when a player hits you if you're in vanish. (Untested)
- Fixed world protections - Fixed making them wayy too large.
- Updated the welcome message - For new + Old players!
- Updated the seasons welcome message to S9. S4 is so 2019.
- Updated teleportation to spawn onJoin.
- Update / Changed Version welcome message to V9 - The latest.
- Added a new worldguard flag to ensure genbuckets aren't being used inside a region.
- Updated warp locations for the End, and the nether.
- Fixed generation worlds for ender and nether.
- Added back /spawn, as per requested. - You can still type /warp and then selecting spawn to teleport back there as well. 
- Updated Wildness location to support from x: 1, and z1 to x 10k, and z 10k. This is to ensure less teleportations to the spawn when using /wild. (Though, this may still happen in some cases, which we can't stop fully).
- Added back Rarity colors to /ceshop!
- Added back rarity colors to Enchantment books. (When bought, and before receiving the enchant.
- Made /ce into an UI for easier accessing.
