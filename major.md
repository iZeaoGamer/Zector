# Welcome to a brand new update v13.0. In this update, we create a new server named OP factions. This is Season 10, since we're continuing from where we left off previously.
# This update also brings in so many Custom enchantments (Compared to OP Factions S9), Envoys, LuckyBlocks, Bosses, and so much more!

## Here is the new v13.0 update changelog:
- Recoded Scoreboards to make it function, and add proper API methods for scoreboards.
- ScoreBoard title now has a colored name.
- Remove multiple scoreboard plugin names, and just implement as one scoreboard plugin.
- Added /pvphud - Shows PvP Scoreboard Information, which show two type of main informations:
1. Durabilities for Armor.
2. Cooldowns for Enchanted golden apples, Golden apples, and Ender pearls.

- Show colored rank name along with the player name on scoreboard.
- Removed a lot of useless shit that didn't need to be on the scoreboard. (Upto 9 lines).
- Added Ender Pearls cooldown, functional as well.
- Fixed enchanted golden apples and Golden apples from displaying the wrong cooldown message and timer.
- Added envoys 2.0.0 recode (I'm mentioning it here because these changes are differences from S9 of OP Factions and S10 of OP Factions).
- Added LuckyBlocks to the server! 
- Removed a lot of useless plugins - We're now on 76 plugins. Before, we were on 116 plugins. Much big improvements.
- Moved server hosting providers to Wither hosting. People say it's good, so we hope they're right.
- Recoded AutoSell to 2.0.0 and how it works! Once again, but should be the fix this time. ;D
- Removed Sell Boosters for now.
- Removed compatibility support for SellAll plugin, and added compatibility with Shop plugin (/shop).
- Auto Sell should no longer lag the server. (Untested).
- There should be no more /shop exploits along with /sell exploits.
- Added a complete /sell recode.
- Added /sell [hand/all/auto]. I'll explain what each of them do:
* hand - Sells items in your hand.
* all - Sells everything that's sellable in your inventory.
* auto - Toggles on/off autosell. Yes, this is now combined with /sell.

- Removed SellAll plugin due to us wanting to be a custom server. ;D + A lot of exploits with this were issued.
- Removed inventory option due to less confusions.
- Fixed crash upon scoreboards.
- Added abbrieviated balance / money. SO for example, if you have $1000 or $1,000, it'll now display as $1k.
- AutoSell now works as expected.
- Fixed AutoSell from still working even if autosell is turned off.
- AutoSell (/sell auto) is now for certain ranks only (Most likely for donators only).
- Fixed crash upon mining LuckyBlocks.
- Added anticheat for: Auto clicker, Kill Aura (Clicking from a far distance), ToolBox detection (Untested), Nuker, and instant break. (Untested) - Try out)
- Fixed crash upon breaking blocks.
- Added staff alerts detection to the anticheat.
- Crates have been recoded!
- Added quick-animations for crates.
- Fixed crash upon Enable().
- Fixed crash upon opening Rare crate.
- Fixed crash upon opening Common crate.
- Removed the following crates:
* Uncommon
* UltraRare

- Added a new crate called “Epic”. It’s the 2nd best crate in the game.
- Keys are now virtual rather than physical. This is so you don’t ever lose your keys if your inventory is full. It’s also to make the server professional, with its all unique color texts above the crates.
- Added the following functions:
* getKeys()
* addKeys()
* removeKeys()
* setKeys() - Just to be safe. May remove this if no other plugins are using this function.

- Floating texts now update live upon opening crate.
- Added duels system to the server! How it works? You can duel a player, just by using /duel ask <player>. To accept a duel, you can type /duel accept [player]. To deny a duel, type: /duel deny [player]
- Added a 10 seconds countdown before the game starts. It comes up with awesome messages as the title. Example: 10 To 8 seconds: Duel against [player], 7 - 6 seconds: Good luck. And the countdown timer from 5-0 seconds.
- Countdown timers can no longer be broken if a player leaves the game. Instead, it’ll teleport the winning player to spawn. The player can win in two ways.
1. By killing the other player in a duel.
2. By the other player quitting the game, making you the prime winner.

- You can no longer duel yourself. What was I thinking? :P
- Countdown display now stops if a player quits the game, making the other player the winner of the duel, and will teleport the appropriate players to spawn.
- Fixed crash upon dueling someone.
- Fixed crash upon countdown display.
- Fixed crash upon player quit.
- The death screen will no longer appear when a player dies in a duels arena.
- Added Crate keys note, which you can get from mining.
- Fixed crash upon breaking blocks.
- Fixed crash upon auto server restart.
- The server will now restart properly.
- The server will now kick players from the server properly upon restart.
- Completely recoded ranks and how they work!
- Completely recoded chat formatting, along with better-ranking security, and better permissioning systems.
- Completely recoded #server-logs 2.0 to make it even better formatting.
- All permissions are already pre-compatible with the new permissioning system!
- Added new chat formatting - So much better than before!
- Fixed permissions from not always working, and therefore, requiring you to relog.
- Added new command: /setrank, also known as /setgroup (Better formatting).
- Added new YouTube ranks: YouTube, and Famous ranks.
- Removed the YouTube rank: MiniYT.
- Removed all the useless ranks that weren't needed.
- Added #public-chat - This chat will track all in-game chats!
- Added #staff-commands - This chat will track ALL commands executed by a member of staff. You can't see this chat because you don't have access to this chat. It's only for Managers and Owners to view.
- Managers and Owners now require Operator to execute anymore commands, rather than permissions its self.
- For the first time since forever, we're finally removing PurePerms, and PureChat support. This is simply because we now have our own grouping, and permissions system. Yay!
- Fixed crash upon executing /setgroup, where the database would eventually disconnect. This issue should no longer occur.
- Added new command: /addpermission - Adds a permission for the user.
- Rank permissions, groups, and chat formatting are now handled coded-side, meaning no one but the owner can access, and edit them.
- Added new functions to identify grouping systems, permissions, and new discord Management API methods.
- Added multi-server support with Permissions and ranks for future reference.
- Added activity checks for #last-seen (on Join and Leave.)
- Recoded #last-seen 2.0 to make it even better, and to make it stand out better than before!
- Added a custom Home system to ZectorPE!
* Type /home [name] to teleport to a home.
* Type /sethome [name] to set a home.
* Type /homeadmin [player] [name] to teleport to another player's home - For admins and above only!
* Type /removehome [name] to remove a home of yours.
- There's now a home limit per user. The higher your rank is, the more homes you'll have.
- Added PlayerVaults limit to Ranks and permissioning systems, rather than implementing pocketmine's methods.
- Added /vanish [on/off] to enable/disable vanish.
- A vanish popup now occurs when you're in vanish. Great for Moderators and above.
- You can no longer use /sethome whilst in vanish, or spectator mode. This is simply to prevent abuse.
- Actively checking database every 60 seconds to prevent future errors.
- Fixed crash upon join.
- /pv 2 and above now works for the appropriate ranks that should have this.
- Added /alias command to Trials and above.
- No longer require player vault permissions for ranks, since rank permissions are already pre-set.
- Fixed server crash upon player quit.
- Added homes to the My SQL database.
- Fixed crash upon using the /list command.
- Added /spectate - Allows you to spectate a player, and instantly teleports to the player.
- Added back /spawn.
- Added chat format to Nametags, except without the message content.
- Removed Faction only nametags, and replaced it with the chat formatting along with faction name, rank, and more.
- Added a new usage: /homeadmin [player] [type] [home]
[player] is the player name you want to enter.
[type] can be two types. One which is list, where the [home] section isn't required, and it'll list all the homes for this user, and two: teleport or tp, where [home] is required, allowing you to teleport to another player's home.
We've decided to make this change because before, /homeadmin was merely impossible to check for a player's home. Now, it's possible.
- Updated Scoreboard to implement proper Rank colored name, as seen in the chat.
- Added /rewards - How this works:
When your inventory's full, items or blocks will automatically export into /rewards, which opens a GUI interface, where you can collect those rewards so you don't lose them.
- Added /inbox - How this works:
It's similar to /rewards, but instead, /inbox only works with Trading. For example: If your inventory's full whilst trading, the item that you receive will be automatically imported into /inbox.
- Added new trading system 2.0!
- Fixed crash upon /trade.
- Added new usage: /trade [ask/accept/deny] [player]
- Fixed crash upon mining blocks.
- Fixed {message} appearing in nametags.
- Added new parameter for Nametag formatting within ranks parameter.
- Added bosses!
- There's now a boss arena! Type /pvp boss to teleport to the Boss arena.
- Added new command and arguments: /pvp [players/boss]
* /pvp players is for PvP arena.
* /pvp boss is for Boss arena.
- Fixed crash upon TNT Explosions.
- Fixed crash upon chatting.
- Added a chat cooldown for ranks below Bedrock.
- Fixed crash upon killing bosses.
- Fixed crash upon killing Spider Boss.
- Fixed crash when using /f home.
- Fixed being able to trade yourself.
- Added new rank colors back to scoreboard.
- Added /rankup - You can rankup to receive better perks, such as more PVS, homes limit increasement, more commands, and more. Yes, I've based it off from Harry potter mainly because why not? Makes it original, etc. - Thanks to <@!355854401379893259> for testing.
- You can no longer receive keys from mining. You can now receive them in LuckyBlocks. (Untested, and may need more revamps, and some BC-Breaks containing this also, which we'll look into.)
- Fixed crash upon /rankup.

**NOTE**
/rankup cannot be obtained from above Guest. This is because of some bugs if we were to change this that could reoccur. Though, we may try to resolve this in a way where it's fair for everyone. Not confirmed yet though.

- Added offline support finally for /alias!
- Alias recode 3.0.0 includes more fixes, optimization, a MySQLDatabase implementation for /alias, and so much more.
- Added new chat formatted text for /alias.
- You can now check for players that are offline, but have joined this server before. How awesome is that? ;D That way, if you want to alias someone that's offline, then you can do so! Just by typing /alias <player> ip/device>. Yay! This is something a lot of staff wanted, which will be provided in V13.
- Fixed player name duplicating in /alias ip and /alias device. Especially /alias device. ;)
- /alias is no longer stored in a config. It's now stored via a MySQL Database, increasing its better benefits within the plugin. ;D
- When using an incorrect type of Alias, it'll now say "Wrong usage", rather than just not work.
- Added a Factions plugin recode 2.0.0, which includes: Many optimizations, bug fixes, and new features implemented.
- Rebranded /f map to open a UI, rather than a message.
- Removed /f top value. We may add this back in the future. We simply don't know yet.
- You can now claim in multiple areas. Before, you could only claim once per faction.
- Fixed crash on /f claim.
- Fixed crash on /f home.
- Fixed crash on /f sethome.
- Factions now handles data via the MySQL Database.
- Recoded /f chat to how it's suppose to work.
- Added new usage: /f chat <chat-type>. If you do not enter chat-type field, it'll choose for you automatically in order.
- Fixed being able to kick yourself from the faction.
- Fixed being able to promote yourself from the faction.
- Fixed being able to demote yourself from the faction.
- Fixed being able to invite yourself from the faction.
- Removed /f accept, and added /f join <faction>. Note that you can only use this command if someone from that faction invited you.
- Updated, and rebranded /f help command.
- Recoded the plugin, separated each sub command into its own classes for cleaner uses.
- Creating your faction now gives you the Leader role properly.
- Added new command: /f fix <player>. This command will reset another player's faction information to fix possible issues to do with the user and the faction plugin - Basically a reset.
- /f claim now requires 3 members in your faction.
-  Removed /f say, and changed it to /f announce - It'll broadcast a title to the faction members.
- Added new role Recruit - Which will be the first role you will receive when joining a faction.
- Leader now has three (***) instead of two (**).
- Using /f home now has a 5 second delay before teleporting. This is to prevent combat logged players.
- Fixed crash upon join.
- Added Online timer and Offline timer to #last-seen. How it works:
OnlineTime basically detects how long they've been playing on the server since they last joined.
OfflineTime basically detects how long the player's been offline for, and when they next join, it'll display that. This is great for activity reasons. Thanks to @MST | Bubbly for sharing this idea!
- Fixed crash onJoin once again.
- Added a new Staffchat recode 2.0.0.
- Changed permissions for it. Soon, we may add it so only staff ranks can use the command. If they are opped, and they're guest, then they'll no longer be able to use the command.
- Reformatted Staffchat.
- Added a way so only staff ranks can see and talk in staffchat.
- Added Server: section to #last-seen chat.
- StaffChat command no longer requires permissions. It now depends on what rank you are. Example: If you're Trial, then you'll automatically be able to use /sc without requiring permissions to do so. In a sense, it is still requiring permissions, but not rank permissions, but merely depending on what rank you are. We plan to implement this for all of our moderation commands soon.
- Added a BRAND new OP Factions core to the server!
- Added all of our custom plugins, combined into a core!
- Completely recoded Custom Enchants, and how they work!
- Removed a lot of useless enchants, and sticked with OP Factions Ce's. You can find what each of the CE's do, by typing /ceinfo.
- Fixed crash upon join.
- Fixed crash upon leave.
Disable core plugin if there's an error when enabling the plugin. This is introduced to prevent bugs, and server crashes.
- Added Enchant remover - More will be explained later on.
- Added Enchantment shop to /shop.
- Fixed crash upon interaction.
- Fixed crash upon break.
- Fixed crash upon AutoSell.
- Fixed crash upon using /mctop.
- Fixed crash upon using /mcstats.
- Fixed crash upon MCMMO Level-up.
- Added Enchantment books to /shop.
- Completely recoded and customized to how receiving a enchantment works. Here's how it works:
* When you use /shop, and select Enchantments, you can select a wide range of rarity types you can use to buy a random enchantment. (It's bought using XP Levels, by the way.) When you buy, you'll get a random enchant book.
If you don't have any CE's of the sort named say Efficiency, then the enchantment level will be on Level 1. If you receive the same book, you can upgrade it to level 2 by doing the exact steps as stated above.
- Added custom lores to Enchantment books, showing you certain information on it.
- Removed /ce, and added a overwritten command for pocketmine's default /enchant command.
- Added our own custom-made Combat logger plugin (Untested).
- /envoys has changed colors.
- A lot of data is now being stored on a MySQL Database.
- Fixed item not giving you the drops on death.
- Removed /ceshop, and Piggy Custom enchant plugin.
- Enchantments shop also includes Vanilla enchants too.
- Fixed crash upon interacting with chests. (Fixed, but still need to fix more relating to this ;/)
- Completely recoded Kits system.
- Added a ton of new kits.
* Here are the following new kits we've added:
* King
* Enchanter
* Archer
* Miner
* God
* WarLord
* Lord
* Once

- Completely revamped donator ranks, and introduced 3 new donator ranks. Here are the following donator ranks available:
* God
* WarLord
* Lord

Those will be the three new ranks you can obtain from the store. This also makes the server Non P2w as well!

- Added the new Kits system to the core!
- Recoded the chest kit to a chest minecart.
- More kits = The more items, and the more ways of retrieving them.
- Fully implemented Enchantment remover. How it works:
* You can obtain Enchantment remover, either by killing bosses, by obtaining Enchantment books, or by obtaining the kit: Enchanter.
Firstly, you can use an enchantment book to select if you'd like to obtain a enchantment remover. If you click yes, you'll obtain the enchantment remover. It's like LuckyBlocks, it has a random selection of chances it will be removed, and a chance of it not being removed. The higher the percentage goes, the more likely the enchantment will be removed. This is a great way to identify whether or not you want to keep this enchantment. The odds are all upto you!
- Removed the "That's not an enchantment book or item" message because of spam reasons.
- Fixed crash upon identifying success rate chances.
- Fixed crash upon identifying whether or not you have enchantments on your item before proceeding to removing/keeping the enchantment.
- Added Essentials to the core.
- Added /trash
- Added /fly
- Added /feed
- Added /nick
- Added /rename
- Added /repair
- Added /freeze
- Added /tpa
- Added /xyz
- Added /reply - Reply straight back to the person without the need of entering the player's name. This only works with the last player that messaged you.
- Added a customizable /tell.
- Added /echest.
- Fixed crash upon TNT explosions.
- Fixed being able to set your nickname as BLANK, therefore abusing /nick system.
- Fixed crash upon using /tpa.
- Fixed wrong error message for /reply.
- Show full usage for /nick if no arguments are specified.
- You can no longer use /tpa on yourself.
- Fixed crash when vanishing yourself.
- Fixed crash when using /sell hand
- Fixed crash when using /sell all
- Fixed crash when auto selling your items.
- Fixed not being able to break blocks when you're in the wild world.
- Added /wild to the core.
- Fixed crash upon using /wild when in console.
- Fixed crash upon using /duel
- Fixed crash upon using /trade
- Fixed "error Creating form" form popping up whenever you did certain actions.
- You can no longer interact with the enchantment remover item - Instead, you can use the enchanted item which will open the Enchantment Remover automatically because it recognizes that you have an enchantment remover in your inventory.
- Disable being able to teleport to wild if you're already pre-teleporting! This is added to prevent bugs and future issues with this.
- Fixed /alias device not generating appropriate users upon join.
- Fixed more duplications of the same player name with /alias ip.
- Added Client ID (CID type) to /alias.
- Added Koth to the Core.
- Generate a new arena data upon first Enable, by defaults.
- Fixed /koth from not outputting a message. c;
- Fixed crash upon koth join.
- Fixed crash upon koth leave.
- Fixed crash upon koth won message.
- Generate default configs properly, including arena database.
- Added a working VPN detection system!
- You'll no longer be able to use VPN's on the server! (Unless bypasses were involved).
- Kick the player that is using the VPN proxy, instead of not kicking them.
- Added /realname command to Core.
- Added /broadcast command to Core.
- Added /clearinventory command to Core!
- Fixed crash upon broadcasting a message to the server.
- Fixed not being able to PvP.
- Fixed Command blocker internal server erroring you upon executing a banned command.
- Fixed Command Blocker configurations not generating within the core properly.
- Fixed crash upon using /iplog.
- Using a / and nothing else no longer returns as a blocked command. This was simply because the command blocker configurations weren't generated properly.
- Added back Combat Hud + new font.
- Fixed crash upon damage.
- Fixed combat logger timer not counting down.
- A message will now appear once you're out of combat.
- When a player logs off whilst in combat, it'll now say the last player that damaged the player, leading to the kill in chat, which will allow them to retrieve the kill.
- Command blocking system whilst in combat added.
- Fixed /iplog not working properly.
- Ensure players don't combat log once the server restarts, by allowing the server to automatically put the tagged players, out of combat within the 5 seconds before the server restarts. Yes, this has been tested to work thankfully!
- Transfer players to the hub once the server restarts.
- Fixed crash within the 5 seconds before restart.
- Send a message to tagged players stating why they're out of combat, making them not log out whilst in combat due to the server restart, thus making them combat logged.
- Send them out of combat before the server restarts - Made it better, and less bypassable. 
- Fixed kills from resetting upon every server restart.
- Fixed LuckyBlocks mined from resetting upon every server restart.
- Fixed User permissions from resetting upon every server restart.
- Fixed Quest points from resetting upon every server restart.
- Fixed /chatcolor colors from resetting upon every server restart.

Why was this occurring?
This was happening because the data wasn't being saved to a MySQL database, leading to the constant stat resets.
This should no longer happen to you, so enjoy!

- Fixed crash when using /chatcolor.
- Added a new permission: "chatcolor.all", which allows you to obtain all the chat colors from /chatcolor. It's just a much more easier way of understanding whether or not they have all the chatcolor permissions.
- Fixed color wools not displaying if you had the only permission: "chatcolor.all".
- Fixed crash when using /f kick.
- Fixed crash when using /f leave.
- Fixed incorrect names within the Boss egg. Now, it states the proper name for the Boss.
- Fixed crash when using /spawn.
- Fixed crash when teleporting to spawn.
- Fixed crash when using /spectate.
- /pvp players is now fixed.
- Added the core to the OP Factions Server finally!
- Upgraded Online Time ( #last-seen ) to 2.0.0.
- Fixed crash upon quit (sometimes). This was due to complications between Online Time, and the server not being able to handle the data. We now use our own version of #last-seen's online time, which is better, and doesn't cause crashes anymore.
- Fixed some weird issues containing #last-seen's Online Time. Should now fully work.
- Fixed crash upon Envoys enabling.
- Added MoneyNotes to the core!
- You can now obtain Money Notes from envoys, and bosses.
- You can now obtain Money Notes in Koth.
- Added protection for certain worlds. At the moment, some of the following are now protected:
* Spawn
* PvP Arena
* Koth
* Some event worlds.

- Added Crates to Spawn!
- Fixed crash upon opening crates.
- Fixed crash upon opening crates whilst offline.
- Fixed crash upon crate finishing after crate opening.
- Set up koth successfully!
- Fixed crash upon using /givekeys.
- Kit Notes are now Minecart chests.
- Added back /sellwand, but the permissions for it are now fixed - Since before, /sellwand could be used by everyone. Now, it's only for operators (/opped players). This was indeed a major bug that had to be fixed in this version.
- Fixed auto generators not working properly.
- Once generators are now coal ore generator, instead of emerald ore generator.
- Once Generator has now received a custom name for the item. This is so people are aware what this item is.
- Added more fence, lowering to the ground in /pvp boss to prevent bosses escaping the arena.
- Fixed incorrect symbols for money. Example: Before, 900k was 0.9M. Now, it's just 900k.
- Fixed incorrect symbols for money. Example: Before, 999k would be 1,000k. Now, it's just 999k.
The same goes for all the other symbols and money.
And yes, this fix is only affective on the scoreboard, since that's the only way symbols like that will show up.
- Fixed crash when using /pvphud
- Added back cooldowns for Enchanted golden apples, normal golden apples, and Ender pearls.
- Fixed Scoreboard sometimes not fully appearing on join until a few seconds later - Sorry Mittins! ;P
- Fixed /ss from not detecting commands properly.
- Fixed /ss from not detecting faction chat, and ally chat.
- Fixed /ss from not being disabled properly when you leave. So when you type /ss after you join, it'd say "Disabled socialspy". Now, it'll say "Enabled Social spy".
- Show error message if used the incorrect arguments in /pvp.
- No longer require permission to buy other mining generators from /shop.
- Fixed server start-up issues (sometimes). This was caused due to a lot of plugins being enabled at the same time on the server.
- Upgraded [item] chat to 2.0.0
- The new item chat 2.0.0 update introduces many code fixes, and optimizations.
- Removed [inventory] - FOR NOW. We may/may not add this back soon. This is all apart of the recode 2.0.0 ;P.
- Fixed crash upon killing zombie boss.
- Fixed crash upon killing witch boss.
- Fixed crash upon quest shop.
- Added new item to quest shop: Random kit.
- Updated quest’s API to fit the new enchantment’s API methods
- Recustomed some messages for /quests to make it look better.
- Added new alias command for /quests, which is: /quest.
- Do not include the word “Boss” in the boss egg item lore (Boss type). (Untested)
- Fixed crash upon selecting Quests shop.
- Fixed Quests menu not popping up when selecting a category from /quest.
- Fixed crash when using /bossegg, and the crash would only ocurr if the boss didn’t exist.
- Added back /thru to the core.
- Added new aliases: /through, and /phase.
- Added /gamemode overwritten pocketmine's default gamemode command.
- Added back aliases for /gamemode: /gmc, /gms, /gma, /gmspc.
- Remove success messages when enabling certain aspects of some features. Only displays if errors are shown within the plugin.
- Added function initWorlds(), loading all the worlds we currently use. Will update it over time or whenever a new world is created (for a specific reason). This is to reduce the amount of worlds loaded at the same time that we might not need.
- Removed WorldLoader as a plugin core feature, and just implemented it to the Main class its self.
