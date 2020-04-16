## V12.0 UPDATE; MAJOR.
## The update that changes everything.

# Welcome to another brand new version: v12.0. This update brings out so many bug fixes, improvements, and implements so many new CE's that will bring your game experience into joy!
# We've also added MCMMO which no other servers have. We've also introduced Acrobatics, and level-up game experiences that you will love and enjoy.
# This update also releases a recode with /enchant and how it enchants the item; Now, it will see the isVanilla() tag (which never happened before), and will detect whether or not the enchant is vanilla. We've cleaned-up enchantItem() function, and implemented isVanilla() tag which will do two actions. 1. If isVanilla() is true, it'll enchant using pocketmine's default enchant functions. If isVanilla() is false, it'll automatically use custom enchant's methods of enchanting.
# Yes, this fixes some CE's if not most from not working properly, such as: Glowing, and some others which were originally reported to not work, which have now been fixed.
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
- Added back Cells - WIP.
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
- Fixed crash upon inviting yourself to the gang.
- Fixed crash upon demoting yourself from the gang.
- Fixed crash upon promoting yourself from the gang.
- Fixed crash upon inviting other players from the gang when they're offline.
- You can now promote offline players if they're in your gang.
- You can now demote offline players if they're in your gang.
- You can now kick offline players if they're in your gang. (/g kick)
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
Double damage: 1-3: gives chance of doing double the damage (like 2%)
Ariel:1-5: Increase damage dealt in air
Deep wounds:1-3: CHance of making player bleed
Backstab:1-3:Increased damage dealt when sneaking 
Vampire:1-3: Convert damage taken to health

Axes

Blessed: 1-3: Clears all negative effects
Wither: 1-5: give enemy wither 
Poison:1-5: Gives enemy poison
Sloth: 1-5: Gives enemy slowness and mining fatigue 
Hallucination: 1-3: Nausea to enemy
Decapitation: 1-3: Chance of dropping head upon kill/death 15% per level
Maniac: 1: GIves haste
Double damage: 1-3: gives chance of doing double the damage (like 2%)
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
* Axes - Damages armor quicker + More critical particles + Strength.
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
- You now automatically levelup when selecting the appropriate race class from Swords and axes. Before, this didn’t work.
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
