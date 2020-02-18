## V10.0 Update; Major
## NOTE:
# This update is a complete re-code of OP Prisons, and there are a lot of bugs that were fixed from the S4 update. We finally bring back OP Prisons with a new season, which should fix all the major bugs.
# API, and some of the changes are classed as "Major", not "Minor". Which may include a lot of featuring-changes made in this update.

- Recoded /enchant completely, added more customization to the /enchant command.
- Leveling toggle now relies on a slider, instead of input fields for less complicated, and buggy method.
- Added Remove Enchantment toggle to /enchant, where you can decide whether or not you want the enchantment to be removed from your weapon.
- Fixed internal server errors when executing /enchant.
- Fixed messages such as: "You are at the maximum enchantment level" appearing even if you're not at the maximum enchants levels. This way was buggy due to the Input field for adding onto the levels. This was a big mistake because some of the time, this used to easily be abused. Good thing I've recoded it completely, aye?
- Fixed remove Enchant toggler from not removing the enchant properly.
- Added a check to ensure whether or not the player's item in hand has enchantments or not before removing the enchant in /enchant. If has an enchant, an error message will return.
- Fixed internal server errors when trying to enchant / remove an enchantment from Experienced CE.
- Lazy Custom enchantment now works as expected, implemented new methods for Lazy CE, making it work better than before. Since the last method was messed up because it was relying on how much EXP a player had, instead of whether you've upgraded to the next level, and whether or not you've mined once or not after you leveled up. If break = one time after upgrade, it'll set to true, so the EXP Max didn't constantly keep decreasing every mine, and only once every levelup.
- Crafting sellable items now properly adds onto the amount of items you're auto selling.
- Added a new Custom Enchant: Auto Sell. There's two ways you can sell now, 1:
1. /autosell - Free, which allows you to turn on/off automatic selling without the need of custom enchantments.
2. AutoSell CE - Can be useful for Custom enchantments related content.
- Inventory picking up items somewhat has a working items amount when selling them. (I say somewhat because it's in BETA, and isn't fully accurate.
- Added AutoSell to /enchant.
- Fixed a lot of bugs relating to Item count being zero when sold using Autosell.
- Added and fixed /shop.
- Protected all of the mines, and worlds required.
- Added Auto mine reset.
- Fixed an issue, where first join would always appear for this player even if they've joined before. (When I mean before, I mean like 5-10 minutes ago).
- Fixed a bug, where players would be able to pvp in plots.
- Hunger no longer drops for the player when they're in plots world. This was due to a bug where players couldn't eat in plot worlds. This is a temporary fix to this until I find a permanent fix for this issue.
- Fixed internal server error when accessing Auto Sell Enchant information from /enchant.
- Fixed description error made in Auto Sell.
- Update enchant description for AutoSell, it no longer reoccurs "inventory" twice in one description.
- Fixed webhooks join/leave messages for OP Prisons.
- LuckyBlocks can no longer be placed.
- Made LuckyBlocks functional.
- Fixed Tokens not being received when breaking some lucky blocks.
- Fixed slight money issues.
- Updated the messages to english, and corrected the grammar on the "won" messages from luckyblocks.
- Corrected /shop grammar to english, and corrected the grammar on the Shop messages.
- Fixed a bug with player that has spaces in their name from not receiving the tokens or money from luckyblocks.
- Sell Boosters should be working now. (Still expect to be some bugs, but most of it should work now).
- Fixed count reset for Sell boosters going to 0 when it shouldn't. (Tested, but the bug may randomly come back.)
- Fixed typo messages in crates.
- The new crates plugin now supports spaced player names.
- Fixed internal server error when interacting with the paper (Sell Booster).
- Fixed a lot of bugs relating to timer display for sell boosters.
- Added back Auto Inventory feature - When breaking blocks, it'll automatically go straight to your inventory instead of dropping on the ground.
- Auto Sell now supports Auto inventory items - It'll count the total items you have in your inventory before selling it.
- Fix spam issues relating to Auto Selling.
- Added a different Bin / trash system, less glitchy too!
- Imported The new PlayerVaults update that is on Factions to OP Prisons S5.
- Added a check to ensure sell boosters can only be used once at a time. This is to get rid of the nasty bugs relating to sell booster count resetting.
- Added hasStarted() check to ensure the sell booster cooldown still continues even upon every server restart.
- Added a notification to let the player on the server know once they're able to use their next sell booster again.
- Fixed timer display upon Sell Booster receive.
- Fixed Inventory from not being sold properly if you toggle on AutoSell inventory feature in /autosell.
- Nerfed some CE's down to prevent anymore super OP items, and tools.
- Fixed some minor dupes relating to Items not going directly to your inventory.
- PvPMine has been slightly changed, thanks to @ItsYTWolfie for the help!
- PvP is now enabled in the PvPMine, not just some parts. Tested by me and @ItsYTWolfie.
- Removed ScoreBoard because for some reason, it caused server lag issues. We may add this back soon, we're not sure yet.
- Nerfed the rankup prices! It's now possible to rankup to places.
- A lot more things are now sellable. ;D
- Charity enchantment now broadcasts every 60 seconds per mine / break. This is to prevent spam. (Thanks to @ItsYTWolfie again for that suggestion)
- Charity enchantment now detects the total amount of tokens given to the player after the every 60 seconds cooldown. This also includes charity giving the total amount of tokens to the online players after the 60 seconds cooldown is over, instead of giving the online players tokens instantly.
- Fixed drops not going straight into your inventory if the inventory feature is disabled in /autosell.
