## V12.0 UPDATE; MAJOR.
## The update that changes everything.

# Welcome to another brand new version: v12.0. This update brings out so many bug fixes, improvements, and implements so many new CE's that will bring your game experience into joy!
# We've also added MCMMO which no other servers have. We've also introduced Acrobatics, and level-up game experiences that you will love and enjoy.
# This major update also brings out combination between Factions and Prisons, which makes Hybrid S1.
# We've also added new PvPMine and Spawn.
# And so much more! The update is endless! This update actually changes everything, and for the better too.

## Here is the new on-going changelog for V12.0:
- Added Classes - When you first join, a UI will popup, asking you what class you'd like to pick for the rest of the season. You can pick a class, which will contain forever features, such as: An effect, MCMMO Levels, Tokens, MonthlyCrates, Pickaxe Levels, and so much more! You can also get an item from Legendary crate, which is called "Class Transfer", where you can use that item to pick for another class in which you can choose from. This item is rare, and can only be found in legendary crates.
- Revamped "Welcome Message", rebranded the player count (in total for this season) to include default Pocketmine player data, rather than implementing it ourselves, making us implement more useless files that would've been an issue later on. Also, for opening too.
- Removed useless Join and leave functions, and added brand new exclusive ones.
- Rebranded, recoded, and revamped the way we store specific player data files. They will now be introduced, and created via one file. One file = A player data file, to make the server easily to handle those player data files just by clicking on one file.
- Added the following functions:
setPickaxeData(), setBlocksData(), getPickaxeData(), getBlocksData(), setChatColor(), getChatColor().

Removed the following functions:
setPickaxeLevels(), setGrayColor(), setAquaColor(), setDarkGrayColor(), setGoldColor(), setGreenColor(), setEXP(), setEXPLevel(), setBlocksMinedBeforeReset(), setBlocksMined(), getTempSellBooster(), addTempSellBooster(), hasGrayColor(), hasAquaColor(), hasDarkGrayColor(), hasGoldColor(), hasGreenColor().
- Fixed crash upon break.
- Fixed crash upon player join.
- Removed Plots.
- Fixed crash upon opening MonthlyCrates.
- Fixed crash upon receiving Temp Sell Boosters (If full on inventory).
- Fixed crash upon ranking up.
- Fixed Pickaxe levels duplicating when changing Classes (Using Class Transfer Item).
- Pickaxe Levels, and Effects will now stay and not clear upon join, and upon death (If using the appropriate class).
- Added Auction confirmation menu.
- Fixed crash upon auto selling items due to our newest API Update.
- Fixed crash when breaking blocks and you've upgraded to the next Pickaxe Levels - This bug was introduced due to our newest API Update.
- Added MCMMO Tokens! You can receive them from crates including monthly crate, and in there contains certain MCMMO Levels for certain types of MCMMO.
- Fixed conflicts between MCMMO Tokens and Class Transfer Orb items.
- Fixed crash when receiving the MCMMO Tokens!
- Fixed Renaming your item not displaying Custom enchants properly when using /rr.
- Custom Enchants are now relying on Item names, instead of Item lores. This is so we can also offer any type of enchantment display (AuctionHouse, Chat display), and much more compatibility for the future.
- Fixed crash upon player join.
- Fixed crash upon renaming.
- Fixed issue where only one custom enchantment would only display after the renaming took place.
- Renamed Classes to better-fit the server.
- Added descriptions of each class to the description field of the UI, rather than the button UI. This is so people can now see more on what each class has.
- Fixed crash upon receiving MCMMO Level-ups.
- Fixed crash upon player death.
- Fixed crash upon player movement.
- AutoRepair now repairs your items in your inventory automatically when moving.

We have added the following new CE's:
BOW

Sniper: 1-5: Headshots with a bow do 0.5x more damage per level

Lethal: 1: summons tnt on impact

Hunter: 1-3: Drop player head upon death 15% chance per level

Lightning: 1: chance of summoning lightning bolt on impact

Paralyse:1-5: Gives enemy slowness, mining fatigue

Piercing: 1-5: ignore armour when dealing damage

SWORD

Headless:1-3: Has a chance of dropping heads 15% per level

Poison: 1-5: Gives the enemy poison

Wither: 1-5: Gives enemy wither

Sloth: 1-5: Gives enemy slowness and Mining fatigue

Hallucination:1-3: give enemy nausea 

Double damage: 1-3: gives chance of doing double the damage (2% per level)

Ariel:1-5: Increase damage dealt in air

Deep wounds:1-3: Chance of making player bleed

Backstab:1-3:Increased damage dealt when sneaking 

Vampire:1-3: Convert damage taken to health

Axes

Blessed: 1-3: Clears all negative effects

Wither: 1-5: give enemy wither 

Poison:1-5: Gives enemy poison

Sloth: 1-5: Gives enemy slowness and mining fatigue 

Hallucination: 1-3: Nausea to enemy

Decapitation: 1-3: Chance of dropping head upon kill/death 15% per level

Maniac: 1: Gives haste

Double damage: 1-3: gives chance of doing double the damage (2% per level)

Vampire:1-3: Convert damage taken to health

Beserker:1-5:gives u a chance of strength for 10seconds

HELMET

Glowing:1: night vision

Drunk:1-3: strength (1level=1level of strength) mining fatigue and slowness

AntiToxin:1: Immune to poison

Implants: Feeds the player every time damage is taken

Meditation:1-3: Heals health and hunger every 30s

Focused:1: immune to nausea


All Armour

Heavy:1-5: Reduces axe damage

Enlightened:1-5: Gives yourself regeneration

Molten:1-5: Sets enemy on fire

Poisoned: 1-3: Gives enemy poison upon impact

Cloaking:1-5: Gain invisibility upon impact

Tank:1-3: Less damage taken from projectiles

Shielded:1-3: Gives resistance while worn

Armoured:1-5: less damage taken from swords


Boots
Endershift:1-5:Regeneration and speed at low health

Gears:1-3: speed boost (fix it as it just gives speed 1 for all levels)

Hulk:1-5: Damage to enemy if taking fall damage


- Fix unexpected crashes due to our newest API Update.

- Rebranded MCMMO to a whole new level!

- We've added the following new MCMMO Types:

* Swords - Chance of bleeding the player. + Strength

* Unarmed - Gives you Speed, and Strength.

* Axes - Damages armor quicker + More critical particles + Strength + Tree Feller Ability.

* HERB - Breaks crops = EXP which leads to leveling up your MCMMO.

* Archery - Bow MCMMO.

- Excavation improvements.
- Adds more features to the MINING MCMMO Type.
- Added /mctop - Shows the top 10 highest MCMMO leveled player.
- Added /mcstats - Shows you/other players mcmmo stats.
- Fixed Archery MCMMO From not leveling you up.
- Acrobatic improvements.
- Lowered the amount of MCMMO EXP you receive when using the MINING MCMMO Skill. This is so it isn't too OP due to Driller.
- Swords MCMMO now works
- You can now have a chance of bleeding the player using MCMMO swords; Just activate the swords ability, and you’ll be good to go.
- You can now levelup just by killing Mobs.
- Added new function: addDeepWounds() - Allows you to add deep wounds AKA Make the player bleed. We name this function to DeepWounds() because it works like Deep Wounds. There was no other name we could think of to name this function other than addDeepWounds().
- You now automatically level-up when selecting the appropriate race class from Swords and axes. Before, this didn’t work.
- Reduced Mining MCMMO EXP to 1. This is due to Driller being too OP.
- Renamed /rr to /blacksmith.
- Fixed crash upon shooting projectiles when lightning strikes. This is because MCMMO didn't recognize the lightning wasn't a player, therefore crashing the server due to lightning not being a player.
- Fixed all enchantments from /enchant 
- Completely redesigned adding enchantments to an item, so it's less messy within the code.
- Changed enchantItem() function to implement isVanilla(), which will detect whether or not this enchantment is an vanilla enchantment, or false for enchant being a custom enchant.
- Changed EnchantConfirm() function to implement isVanilla(), which will detect whether or not this enchantment is an vanilla enchantment, or false for the enchant being a custom enchant.
- Lowered the amount of MCMMO EXP you gain from:
* Swords MCMMO
* Axes MCMMO
* Unarmed MCMMO.
* Wood Cutting MCMMO.
- Unarmed now has a 0.2% chance of activating disarming. Thanks to @BST|TimeToWreck360 for the suggestion.
- Fixed crash when activating shielded CE.
- Shielded CE no longer crashes the player or server.
- All enchantments from /enchant now work. This is due to poorly coded functions, and files. Now, it's been made to work with all enchantments (Including CE's)
- Some Custom Enchantment levels effects should no longer plus one a effect. Example: If I were to have Gears Level 3, the effects amplifier would be 4, rather than 3. Now, the amplifier will depend on the amount of CE levels you have. (Untested, and still under development. - May work on more relating to this if need be).
- Fixed Acrobatics rolled system from giving you fall damage even if the acrobatics rolled was successful.
- Completely redesigned, and recoded Cells.
- Added new Ce's:
* Dragon Hunter - Has a rare chance of finding Dragon eggs whilst mining. This can be used later on when creating cells.
* Beaconator - Has a chance of finding Beacons whilst mining. This can be used later on when creating cells.

- Fix typo for Guardian CE. It's meant to be Guardian, not Gaudian! Silly me.
- Added "NEW" tags for those categories and CE's that are classed as "NEW" for this season in /enchant.
- Added a new parmater to Enchant - string $enchantClass
This will be used to identify the enchant name / id class just for future implementations. With this, we've added:
* A error message - The enchantment you specified must either match more of the current enchantment level. The enchantment level you specified can't either:
A. Be the same as the current enchantment level.
B. Be less than the current enchantment level, since then you'll be wasting more tokens! Let's be safe, aye, and do it the easier way = Less complaints of losing tokens over having the enchantment level less than the current enchantment level you have.

- Added a null check to ensure getLevel() isn't null when selecting a enchantment that you haven't yet received. If getLevel() is null, it'll return the level as zero. getLevel() will only become null if the enchantment selected isn't on your item.
- Upgraded the Tokens cost for Beaconator and Dragon hunter. Thanks @IST | YT for that!
- Removed LifeSteal from /enchant - It was meant to be removed, but for some reason, it was still displaying in /enchant.
- Added Tree Feller ability.
- Added new CE: KillAura. Description: Hits Multiple entities at once.
- Fixed DeepWounds from being too overpowered. Because of this major fix, I have decided to buff the max enchantment for DeepWounds to Level 10. Trust me, it isn't as OP as before. Hence why I buffed it. Aren't I just a genius now? ;P
- Fixed /mctop from not updating until the server restarts. It now updates live, on the server.
- Removed Custom Enchantment: Explosive because of how OP it was. We have replaced this with Kill Aura Custom Enchant, which is explained above.
- More than one entity should now be damaged with Kill Aura Enchantment. The more Levels you go up with Kill Aura CE, the more further you can hit the mobs or players. The max is 3 because of its OPness.
- Added back the good ol /vanish system
- You can no longer be damaged in /vanish.
- You can no longer be killed in /vanish.
- Recoded how /enchant stores data - Instead of retrieving Player data using its player.yml file, it'll now create a new file called "data.yml". This will offer: Player name, Enchant name, and Total cost. This is all stored in the data.yml file, and this is also apart of the S7 data recode update.
- Fixed a bug, where removing all of the enchantments from /enchant would still show up as enchanted within your item. This bug was introduced back in S5, and should've been fixed in S6, but for some reason, the new update removed it. :think: . Though, this fix should be re-added, and ready for S7 of OP Prisons.
- Fixed enchant data not being stored properly.
- We’ve been working on adding even more CE’s. In today’s update, I’ve added atleast 12 new Custom enchants that will more-benefit the server, and make the game more enjoyable. Here are the following new CE’s we’ve introduced, the descriptions of each of them, max levels, and the type of item this can be allocated on;
* Nimble - Increases mcMMO XP gained in Acrobatics while equipped. Max: 5. Type: Boots
* Skilling - Increases mcMMO XP gained in all GATHERING skills while equipped. Max: 10 Type: Weapons and tools.
* RagDoll - Whenever you take damage you are pushed far back. Max: 4 Type: All Armor
* Obliterate - Extreme knockback. Max: 5 Type: All Weapons
* Ravenous - A chance to regain hunger. Max: 4 Type: Axes
* Stormcaller - Strikes lightning on attacking players. Max: 4 Type: All Armour
* Voodoo - Gives a chance to deal weakness. Max: 6 Type: All Armour
* Godly OverLord - A very large permanent increase in hearts. Requires Overload III enchant on item to apply. Max: 3. Type: All Armour
* Training - Increases mcMMO XP gained in all COMBAT skills while equipped. Max: 10 Type: Weapons
* Skill Swipe - A chance to steal some of your enemy's EXP every time you damage them. Max: 5 Type: Swords
* Dodge - Chance to dodge physical enemy attacks, increased chance if sneaking. Max: 5 Type: All Armor

- Added back LifeSteal.
- We’ve added 3 more new Custom Enchants to the collection! Here are the following we’ve introduced:
* ArrowLifeSteal: A chance to steal health from opponent while fighting Max: 5 Type: Bow
* Master Mob Killer: Massively increases EXP drops from mobs. Requires Mob Killer IV enchant on item to apply. Max: 4 Type: Sword
* Mob Killer: Increases EXP drops from mobs. Max: 4. Type: Sword

NOTE

Mob Killer enchants is useful for when killing mobs at spawn. You’ll be able to obtain more XP, which leads to being able to buy repairs using /blacksmith, and being able to convert using XP as Currency by typing /converter.
- Fixed enchants becoming free in /enchant, and not reducing your tokens.
- Cleaned-up Auto Restarting.
- We've removed the following functions from AutoRestart system:
getRestartTimer(), getEarlyTimer(), setRestartTimer(), and setEarlyTimer(). This is simply because it was too buggy to handle.
- Restart Timer is now configurable.
- Restart Timer now relies on minutes, not seconds.
- Fixed a bug, where Restart Timer would be buggy, and wouldn't always restart as it should do. 
- Broadcast announcements for restarting is now more better, and easier understandable. Example: 2 minutes till restart would broadcast instead of 2:00. This was sometimes very confusing as to what it meant, so we've decided to add this change for the better as well.
- Fixed slowness being too OP on Sloth.
- Fixed slowness being too OP on Paralyse
- Fixed crash upon activating Skill Swipe.
- LifeSteal now has 1% per level chance of activation.
- Wither now has 1% per level chance of activation.
- Poison now has a 1% per level chance of activation.
- Fixed crash caused by OverLord and max health.
- Lightning now activates on players, rather than on blocks.
- Lethal now activates on players, rather than on blocks.
- Hallucination now has a 1% per level chance of activation.
- Fixed Godly OverLord dupe glitch, where hearts would endlessly regain health without any max health limits.
- Godly OverLord now requires OverLord 3+ to activate.
- Obliterate Custom Enchant has been debuffed to Level 1. This is due to its OPness.
- RagDoll custom enchant no longer takes fall damage upon landing after activation took place.
- Storm Caller now deals Damage to the attacker.
- Fixed amplifier for Poison.
- Fixed amplifier for Wither.
- Obliterate now has a 1% per level chance of activation.
- RagDoll now has a 2% per level chance of activation.
- Storm Caller now has a 2% per level chance of activation.
- Voodoo now has a 2% per level chance of activation.
- Messages for all MCMMO related custom enchants. (Skill Swipe, Training, Nimble, etc etc) now appear once enchant is activated.
- You can now take fall damage in PvP Mine. In season 6, this wasn’t possible.
- Added cooldown messages. Messages such as:
* When a skill becomes deactivated.
* When a skill is activated again / refreshed.

- Added Fireworks upon activation and deactivation of your MCMMO.
- Fixed Archery MCMMO from not working. Now it does!
- Fixed disarming from not working as expected when using Unarmed MCMMO. (Untested)
- Added new functions for fireworks.
- Added explosions to fireworks upon activation / deactivation of MCMMO.
- Fixed fireworks not working upon activation / deactivation of MCMMO.
- Added a functional working cooldown notifications! (Will add cooldown error in the future).
- Finally added Cooldown Error messages with MCMMO.
- You'll now be able to know how long until you're able to use the ability again for MCMMO.
- FireWorks with MCMMO now works as expected! No more unexpected bugs!
- Fixed an issue, where fireworks wouldn't activate if one ability is already enabled during that time.
- Fixed Archery not working once again.
- Fixed swords working with Archery - Basically you can get swords to level-up archery levels. This shouldn't of happened, and we've since then patched this issue.
- Fixed MCMMO from still giving you EXP even if in a protected area.
- Mining for keys is now a lot harder, and rare to obtain (Without KeyPlus custom enchantment).
- Excavation is no longer as OP when leveling up.
- Added Contrabands! - Finally! We've added it for bedrock edition! Contrabands.

What is Contrabands?
Contrabands, is essentially lootboxes, but as a different name. It offers the speciality of gaining really awesome rewards, such as: Bosses, Keys, Custom Enchants, MCMMO Tokens (High amount of levels), Ranks, Pickaxe EXP, Godly pickaxe, Godly Sword, and Godly armour.

- Fixed player inventory from disappearing after opening it a few times.
- Added spaced player names support!
- Completely recoded Autosell, and how it's suppose to work.
- Auto Sell is now supported by SellAll plugin.
- Cleaned-up a lot of shitty codes that weren't even needed, when the Sell All plugin did it, so there was no point of duplicating the codes from different plugins.
- Renamed option to "sell every 10 seconds" in /autosell.
- Fixed Autosell from not working when both options have been set to false, when enabling it, it'll stop working. Weird bug I know, but this should be fixed. (As tested).
- Removed Sell Timer system, and just allow pocketmine's default task timer to do the job. Less buggy too.
- Auto Inventory Sell is now more powerful than ever - It'll start detecting more than once whether or not your inventory is full. This is simply for security measures, which shouldn't be anyway to bypass this if turned on. It may sell inventory more than once, but that's simply for security measures, attempting to sell inventory more than once so nothing get's in the way of its security task.
- Fixed duplication glitch with /sell inv, and Auto sell (Inventory feature). This was because before, it wasn't fully supporting the SellAll plugin. Now, it does, so no matter what happens, this glitch should never happen again. Thanks for reporting this dupe glitch, <@!640034352067117078>!
- Added a notice / warning for setting both options to true in /autosell. Yes, this is a warning to let people know that setting both options to true will infact not work. This is because AutoSell options do not go well together. You need to decide which option to use before making it work. This is for those confused about why they both don't work together. Well, now, there's a warning message when using /autosell. Very useful!
- Fixed Fireworks MCMMO Deactivation message and action from executing from all online players even if they never executed the MCMMO Activation message. This was simply because before, it was recognizing all online players. Now, it only relies on the one person executing the ability deactivated message.
- Added a error message when enabling both auto sell options in /autosell.
- Added a "Updating Auto Sell Settings" message.
- Added a "Saved Auto Sell Settings Message".
- Added Tokens Notes, and Bank Notes (Money Notes) to Hybrid S1
- Fixed OverLord from crashing the server whilst logging out during combat. (Same goes with GodlyOverLord).
- Fixed GodlyOverLord crash upon player join (After player has left the server whilst in combat, and joins back again).
- Fixed Custom enchantments not working when opening Contrabands. This would happen most likely because Contrabands plugin was sometimes loading before the Custom enchants plugin was, leading to this error because it didn't notice a change between the enabling state.
- Changed Custom Enchants function to onLoad() to ensure the plugin get's loaded before any other compatible plugins get loaded.
- Fixed Aerial and Backstab enchants from becoming free in /enchant.
- Fixed another crash for OverLord (Untested).
- Do not activate certain custom enchants in protected areas.
This fixes issues raised to do with custom enchantments activating in protected areas, which shouldn't be enabled.
- Make Auto Repair custom enchant for Weapons and tools only. This is to reduce how OP it is, especially on armor.
- We’ve rebranded our gamemode to combine OP Prisons and OP Factions together, making it Hybrid S1.
- Added /ceshop!
- We’ve rebranded the way rarities work with Custom enchants!
- Added new rarities:
* Epic
* Legendary
* Godly

- Removed Mythic rarity.
- Fixed crash with Archery MCMMO.
- We’ve reorganised Custom enchants into different rarities (appropriately)
- Fixed helmets custom enchantments from not being compatible. This was because of a typo made with Helmets type.
- Lazy CE shouldn't be in common category in /ceshop. We've moved Lazy CE to its appropriate category (Uncommon).
- Added Spawner stacking + Mob stacking to the server!
- Activated Redstone; Currently in BETA.
- Fixed crash upon interaction with Common books.
- Fixed unused $ signs being added to /ceshop, when it costs tokens, not money.
- Added a new restart system; Less buggy.
- Fixed restart spam.
- Restarting the server no longer transfers you to a server (Hub).
- Added basic implementation for use of Off hand.
- Fixed Contrabands from removing your part of the inventory.
- Added the following new CE's:
* Name: Recovery
Information: after killing a player gives regeneration for 5 sec
What item: chestplate
Rarity: legendary
Levels : 5
* Name: adrenaline 
Info: after killing a player you gain strength for 5 secs (each level is a higher level of strength)
Item: chestplate
Rarity: godly or legendary
Levels: 2
* Name: Mini Sell
Info: Has A 0.1% Chance To Double The Amount Of Money You Got From Mining (Autosell Must Be On To Work)
Item: Pickaxe
Rarity: Legendary
Level: 5

- Added Item stacker - When you drop two items that are the same, it'll stack.
- Added Trading UI system!
- Fixed Player flickering issue - We’ve finally fixed a bug, where every 1 second, players would dissappear, then reappear. This bug was known for some time, in which has been fixed. Yay! No more players flickering issue. ;D
- Added back /wild! Better than ever.
- Allow /wild to only take you to the "wild" world.
- Fixed /wild from putting you under the ground.
- Added a detection for /wild, where when you're underground, it'll automatically teleport you above ground, thus making it possible to not take damage.
- Fix crash when using /wild. ;-;
- Added particles when teleporting to wildness.
- Changed teleportation message for less confusion.
- Added Custom names support with Item stacking.
- Items now stack with custom names (when dropped near each other.)
- Added basic implementation for Envoys.
- Added /envoy - A command to teleport to the envoys area.
- Set up rewards for envoys.
- Added [item] and [inventory] back! - For those that don't know how this works, whenever you type [item] or [inventory] in chat, it'll display details about the item you're holding (for [item]), and for [inventory], it'll display your whole inventory in chat along with enchantments display.
- Add spaced player names support to Envoys.
- Spawners now work at spawn.
- Added Generators. Generators can be used to generate blocks above the other block. With the items you collect, you can sell the dropped items using auto sell, or /sell.
- Recoded LuckyBlocks to 2.0!
- We've rebranded LuckyBlocks to make it so you'll have a percentage of good luck, and bad luck. Will you be lucky?
- You can now receive certain kits from Good rewards for LuckyBlocks.
- Custom sounds added to LuckyBlocks (If bad luck occurs).

- **We've added even more new Custom Enchantments!**
Here are the following new Custom enchantments we've added to Hybrid S1:

* Annihilation: Increase damage the lower your opponent's health is. Max: 10 Rarity: Rare Type: Weapons
* Bleed: Have a chance to multiply your damage. Max: 10 Rarity:  Legendary. Type: Weapons
* JackPot: Have a chance to earn money while mining. Max: 5 Rarity: Legendary. Type: Tools
* Luck: Increase your chance of getting a lucky block. Max: 1 Rarity: Godly. Type: Tools
* Monopolize: Have a chance to steal xp from your opponent. Max: 5 Rarity: Godly. Type: Weapons
* Resist: Reduce knockback effects. Max: 3 Rarity: Legendary. Type: Armor.
* Shatter: Break your opponent's armor faster. Max: 5 Rarity: Legendary Type: Weapons
* Stun: Have a chance to stun your opponent. Max: 5 Rarity: Godly Type: Weapons
* Velocity: Increase the speed of your arrow and make it travel straighter. Max: 5 Rarity: Legendary. Type: Bows

**NOTE**
Those custom enchantments have been currently untested, so bugs may occur with this.

- You now have a rare chance of receiving Emerald Ore generator when mining stone.
- Rebranded Auto restarting system.
- Allow full formats (includes hours, minutes, and seconds display text).
- Server now restarts every 1 hour and 30 minutes.
- Fixed crash with LuckyBlocks. (Untested)
- Fixed crash upon using JackPot Custom enchant.
- Fixed TNT from crashing the server when bad luck happens. (Upon spawning TNT).
- Fixed crash for TNT.
- Fixed TNT not exploding blocks, and it'll only damage players.
- Blocks will now automatically direct to your inventory upon explosion. This is to prevent server crashes, and lag with the server.
- Fixed crash upon Item stacking.
- Having a full Inventory will no longer allow you to break blocks until you clear your inventory.
- Brand new colors when having a full inventory.
- Fixed GodlyOverLord from being too OP. This is to prevent further server crashes.
- Added protection for spawn, and Koth.
- Fixed koth fall damage issue when dropping down to the koth arena.
- Fixed parts of spawn not being protected properly.
- Fall damage is now enabled once you're in the Koth Arena.
- Added a complete shop recode, including:
* Generators shop (Includes Auto Generators)
* Markets (Sells included)
* Spawners.
* And so much more!

- Fixed crash when using /shop.
- Fixed crash when receiving the items.
- We've done a complete reconomied (Also known as a Money balance, and tokens revamp - Basically, changed the way they're displayed).
- Money now displays in commas, just like normal numbers (In vanilla-wised concept.) So for example, 1000 would now display as 1,000. The same goes with Tokens also.
- Changed the way ScoreBoards updates, and generators;
- We've reorganised a category, renamed a category called "Hybrid" via scoreboards, which displays: Faction STR, Faction Money, Rank Up Cost, and Rankup Name. You're probably wondering:

Where is the prestige information?
Well, Prestige information will be shown to you once you've ranked up to Z mine. This is due to ScoreBoards limitations in vanilla having the maxed lines 15. It'll automatically update to Prestige information once you're at Z rank, don't worry about that!

- The new money reformatting update has been added to scoreboards.
- The new Tokens reformatting update has been added to scoreboards.
- Changed the way: /seenmoney, /mymoney, and /topmoney is formatted; In terms with display.
- Changed the way /seetokens, /mytokens, and /tokentop is formatted; In terms with display.
- We’ve changed the way unbanning, unmuting, and removing warns on a player works.
- Unbanning a player using /pardon, or /pardon-ip no longer broadcasts to the server. Only to the sender.
- Unbanning using /pardon or /pardon-ip now broadcasts the logs in <#700688869485707276> along with the reason of the unban. Reasons can have spaces in them without requiring “”.
- Unmuting using /unmute now broadcasts the logs in <#700688869485707276> along with the reason of the unmute. Reasons can have spaces in them without requiring “”.
- Unmuting a player using /unmute no longer broadcasts it to the server. Only to the sender.
- Unwarning a player using /removewarn now has warn points you can take off a specific player. The real usage is now: /removewarn [player] [warn points] [reason]
- Unwarning a player now has a reason section you need to fill out, which then broadcasts it to <#700688869485707276>.
- Fixed warns from not broadcasting properly in <#700688869485707276>.

**Why did you update this?**
I’ve decided to update this to better our security system. For example, before; /pardon-ip would broadcast to the server. This was very wrong in doing so due to the ip being broadcasted to the server. That’s very poor security if we were to continue doing this, and would be bad for our server’s reputation.


- Looting and Fortune enchantments now work as expected.
- Fixed Unban, and Unwarn commands from receiving the wrong reasons.
- Completely recoded Spawner stacking + Mobs stacking!
- Reformatted colors with nametags for Mobs that stack.
- Fixed /shop from not being able to buy and sell multiple amounts. This would lead to internal server errors.
- Fixed looting with the new Mobs stacking system.
- Added the following new spawners:
* Spiders
* Pigs
* Iron Golems
* Blaze
* Cows

- Iron Golems now drop Nether star as well!
- Changed the way stacking a mob spawner works - You now need to interact with the current spawner for it to stack, instead of placing the spawner near the other one. This is to prevent buggy spawners not stacking as well as they should. The more they stack, the more that'll spawn.
- Fixed a major dupe glitch with Auto Generators - It may still display duped items, but it's not actually in your inventory; Just a visual glitch!
- Fixed crash when placing Auto generators, and the chest.
- Fixed multiple crashes when leaving the game and the Auto generators are still continuing.
- Fixed crash when unloading chunks that have chests included in them.
- Added Chat Rewards - Chat to earn money! This includes a leveling-up system when chatting. With chatting, you can gain "Chat XP", which is used to levelup automatically.
- Fixed crash upon ranking up to the max prestige.
- Added /coinflip - Replacing this from /jackpot. Jackpot is being removed due to issues raised to do with this. /jackpot will be replaced with /coinflip.
- Fixed crash upon form UI confirmation.
- Fixed bug, where the form would send to the player that had put a coinflip up using /cf add, instead of the sender (the user that used /cf list).
- Fixed bug, where /cf cancel would bring up internal server errors when the coinflip was never used.
- Fixed fireworks deactivating for everyone even if you were the only person that originally activated them. (DOUBLEFIX)
/tpa, /tpdeny, /tpaccept, and /tpahere can no longer be used in Mines, and prestige mines. This is to prevent cheating.
- Added Blocked-commands for certain worlds.
- Fixed bypasses to blocked commands.
- Fixed koth respawn positions issue.
- When you die during a koth game, it’ll now teleport you to the koth warp.
- Fixed internal server errors when using commands.
- Fixed wrongful blocked messages from worlds that didn’t have blocked commands in them.
- Added bosses - The proper way.
- Added abilities to Spider boss.
- Added a respawn timer for Zombie boss to be every 30 minutes.
- Added rewards to Bosses. How they work?:
* When a player get’s the most damage from the boss, they will receive more rewards. Everyone else that damages the boss only get’s one reward.
- Added trap to spider boss that doesn’t last long.
- Fixed internal server error upon killing zombie boss.
- Spider is now the best and OP boss, along with better rewards.
- Fixed crash upon auto boss spawn.
- Bosses will now spawn in the PvPMine.
- Retexted messages.
- Traps for Spider boss now has a chance of activating.
- You can now only spawn one boss at a time.
- Added Sell Wands.
- Added Sell Wands rewards to Spider Boss.
- You can now interact with a chest using a diamond hoe to sell contents inside of a chest. (Yes, Sell wands is what I'm referring to. ;P)
- Fixed crash upon using sell wand.
- Completely recoded envoys 2.0!
- Added multiworld support. This means Envoys should no longer locate in a world that it shouldn't be in. Example: The envoys should spawn in the wild. If multiworld support wasn't enabled with this, then envoys would locate to worlds that shouldn't even be located at, because Envoys spawn in one world. - In other words, envoys used to spawn in different worlds if the position is the same as each other's. When it shouldn't do that.
- Rebranded rewards along with chances system + Stable and Smooth chance system.
- Removed /envoy to teleport to the envoys spawn position, and added /envoys, where you can select a list of envoys and their positions so you can go and find them.
- Envoy Rewards are now fully set up and ready to work. 😄
- Added Koth rewards
- Completely recoded Teleportation timer when teleporting to certain warps.
- You can now move whilst teleporting. The cache is if you move from 3 blocks within your original position when you originally executed the command, it'll cancel your teleportation.
- Fixed N Mine from not being able to be teleported to if you're above N mine.
- Added crates, completely redesigned to how they work! - Done, and will be updated on the todolist LIVE.
- Crates can now be instantly opened.
- We've revamped the contents of MonthlyCrates, and what you can receive from them. Another thing done on the todolist. Get hyped everyone! We're almost there!!
- Added bosses to Legendary crates. (Specifically Spider boss).
- There is now a 0.01% chance of gaining Generators (Depending on which block you mine at the time). So say if I was mining emerald blocks, I could get a Emerald generator. Thanks to @CST Zach Games YT for this suggestion!
- Added Mining rewards, better than ever!
- Instead of giving them the keys directly, it'll now come up in a "Crate key note" whilst mining. You can use that to claim a certain key depending on which one it states in the note.
- You will now be teleported to our newest spawn on teleportation when you join the server.
- Completely recoded Bosses, and how they’re made.
- Removed Zombie and spiders entity types as bosses, and implemented it as its own Entity type.
- Added human skins for both bosses.
- You can now use a spawn egg to spawn a boss in - Basically bringing back the Spawning machanic.
- Fixed internal server error upon interaction.
- Fixed constant errors popping up.
- Fixed crash upon killing Zombie boss.
- Bosses no longer conflict with mobs.
- Fixed crash upon zombie and spider kill.
- Bosses deal more damage to you than they did before.
- Added new broadcast message for placing a spawn egg in PvP Mine.
- Corrected for Auto boss spawn; display /boss instead of /pvpmine, since that’s not a command.
- Fixed crash upon join and instant leave. This could occurr when things such as Internal server errors upon join occurred, leading to the crash. This can also occurr if you’re trying to abuse a glitch or a bug.
- Added wild 2.0 recode!
- Fixed crash upon /wild teleportation.
- Fixed bug, where after teleported is success, it’ll keep saying “Failed to teleport”.
- Added some safety checks to ensure server crashes do not happen.
- Fixed crash upon Bleed enchant, and using it on Zombie boss.
- Fixed bug, where teleporting to locations would get rid of your effects within the class. It now activates forever, unless you change your class mid season.
- Modified properties to make bosses less OP, as in attack damage, and in general; Better to battle.
- Added Quests 2.0 recode.
- Added /quests - Which implements Quests shop, where you can buy items using Quests points. You can gain Quests points by doing daily quests. The quests update all the time, so you can do different quests whenever.

- Added Drops pouch - If you kill a player, the player will drop a Drops pouch. You can tap anywhere to redeem their stuff they originally dropped.
- Added Custom death messages.

- Added WorldBorder 2.0 recode. - Mark as complete in the todolist. Not much further to go now before Closed beta. ;D
- Fixed being stuck in the world border. You should no longer get this issue. ;D
- WorldBorder only affects the factions world.
- Added ExcavationMine warp in /mines.
- Brand new messages added to WorldBorder.
- Added ClearLag 2.0 recode.
- Removed more useless plugins.
- Fixed Zombie boss from being able to be spawned even if a boss has already been spawned in the area.
- Clear Lag no longer clears bosses.
- Fixed being able to receive Legendary keys for free in /quests.

- Fixed crash upon enabling server.
- Added an error message for if the enchantment ID is not found in the Custom enchantments data. If you get an error like this, as an example: "Failed to enchant. Reason: The ID 392 no longer exists on the database. Please send this ID 392 To Zeao on discord so he can take a look and fix it."
then this means the enchant you're trying to enchant doesn't exist. This prevents internal server errors, not knowing the cause of the problem. If you get an ID 392, then that means there was/is an id in the database 392, but it doesn't exist in any of the enchants data. If you get an error like it says above, please DM me, so I can resolve it. Since some IDS may have had a typo added to it. The good thing about this new erroring system, is it won't take away your enchant book if you do get an error like this, so you can go along with your day, report the bug, and hopefully it'll be fixed ASAP.
This is a much better way of handling errors than receiving "Internal server errors". More within this system will be implemented to all of our plugins in the upcoming updates This would only occur if an instanceof wasn't found, or if a check wasn't added, to where the error would come in. Errors such as: Undefined variable, or other undefined issues, will not be able to be fixed within the new erroring system.
- Add knockback to players when they try to interact with a crate that they can’t use because of an error.
- Added new error message: “You do not have a crate->getName() key”.
- Fixed kills from resetting.
- Fixed Quest points from resetting.
- Fixed LuckyBlocks from resetting.
- Added /ce remove - Allows you to remove a custom enchantment from your item.
- Removed /enchant. This is because we don't need this system anymore, and future enchantment holders can be displayed in the Enchantment Table form UI (Which will be added tomorrow hopefully). (Vanilla enchants)
