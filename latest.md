## V10.1 UPDATE; Minor

- Fixed /enchant exploits.
- Fixed /enchant from causing you to get enchantments for free.
- Fixed information in /enchant from not giving you the token cost and information.
- You can now enchant tools using /enchant
- Renamed command usage from /enchant pickaxe to /enchant tools
- Updated sell prices, made it better.
- Fixed permissions for donor mines.
- Removed /tpa, /tpahere, /tpaccept, /tpdeny, /sethome, and /home from players and lower ranked staff members.
- Completely re-coded /enchant, and updated version to 2.0.0
- Fixed many more /enchant dupes, exploits, and issues.
- Added an enchantment confirmation page before buying.
- Cleaned up a lot of /enchant codes that weren't even needed.
- Removed alot of the functions that did the same thing, but different enchantments.
- Added a basic function for enchantment and its types - All in one function. How this works:
1. Function for selecting which enchantment name to enchant.
2. Function for choosing how much levels you'd like to select, and its enchant information.
3. Function for Confirmation page.
Done. It'll either enchant your item in your hand, or it'll say you don't have enough tokens. Depending on how much tokens you have.
- Vanilla descriptions are now handled from the config file, rather than in the codes.
- Added function for checking the vanilla enchantments.
- Updated vanilla enchant descriptions.
- Vanilla levels from /enchant are now handled directly from the config files.
- Clean-up a lot of the player data codes.
- Removed all the functions for getting the cost of the player, and setting the cost of the player, and moved to the enchant plugin its self and replaced it with getTotalCost() for getting the total cost of the enchant + the levels the player selected, getStarterCost() for getting the cost of the enchantment per level, and setTotalCost() for setting the total cost of that enchantment type.
- Clean-up a lot of useless events and codes that was recently removed from the plugins.
- TokenCost now adds it up properly. - Example: it'll x by the levels, not double it even more every time. Example: 100 x 60 = 6k, so if you were to get enchantment levels of 60, it'd now cost 6k, rather than costing more than that. So basically, it now time's it properly.
- Added payment information before buying enchantments, which displays:
1. The total amount of tokens (Includes the levels you selected)
2. The enchantment name
3. The amount of levels you selected.
It will ask you if you're sure you'd like to preceed this purchase. If you click yes, it'll load the purchase, and will let you know whether or not you have enough tokens to buy this enchantment. This proves it works lik a charm.
- Not enough tokens error will now work like before, no matter what levels you selected when attempting to buy this enchantment if you don't have enough tokens.


### So let's recap:
The more levels you select for enchanting, the more tokens it'll cost.
Before, it'd double it more than once per level. This means it'll be at a incredible amount of tokens which wouldn't be right. This would lead to it being impossible to know how much tokens each enchantment costs, because of:
1. It wouldn't display the tokens cost information.
2. It wouldn't display the confirmation page, making it impossible to know the total tokens cost of the final selection.

This all should now be fixed, and time's it up properly.
