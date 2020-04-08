## V11.3 UPDATE; Minor

- Ranking up to prestige now takes away your money.
- Fixed internal server error when ranking up to prestige.
- Fixed internal server error on prestige, where it would attempt to teleport you to spawn, but failed.
- Fixed internal server error upon opening your inventory.

## AuctionHouse Updates
- Added Auction Limits.
- Fixed "can't afford bid" not showing when having no previous bids.
- Fixed bid amount item not updating when too little money.
- Add more info to auctioneer auction claim message.
- Added option to claim all bids.
- Better validation for form inputs.
- Fixed missing filtered text due to menu simplification
- Make the auction creation menu more user friendly

## LuckyBlocks Updates
- LuckyBlocks receiving rewards are now handled with Action bar message, rather than chat message. Meaning the reward messages for Luckyblocks aren't chat messages anymore. They're now vis action bar message.

## PRISON UPDATES

- Mine reset now teleports you to the warp location of the specific mine - Before, it'd teleport you above the mine, which did impact server crashes issues, which should be now resolved. SO for example, if you're mining at Mine C, and the mine resets, you'll automatically be teleported to Mine C warp location.
- Seperated /rankup and added /prestige - This fixes errors relating to /prestige, and /rankup from causing wrong messages. This also fixes errors relating to zero money you need to prestige sometimes. We've added all the checks to ensure /prestige doesn't get abused as well as /rankup.
- Prestiging now works! Just type /prestige if you're at Z rank, and boom! You'll get prestiged! (If you have enough money to do so).
- Money to Prestige now fully works. No more 0 more money needed errors for Prestiging.
- Fixed N Mine not being accessable if you're above N Mine. This error would happen when you've added warp setting "Custom Search Bar" to false.
- Fixed crash on mine reset.
- Fixed internal server error when ranking up to certain mines.
- Fixed internal server error when typing /rankup command really fast.
