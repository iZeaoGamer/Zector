## V11.2 UPDATE; Minor

- Fixed crash on voteparty.
- Fixed a bug, where vote parties would cause the server to crash whenever your inventory is full, and a pickaxe is attempting to be added to your inventory.
- Pickaxes will now drop out of your inventory when you're full on inventory. (VoteParty)
- Added AFK detector to OnlineTime! How this works: When you're A.F.K for a certain amount of time, the online time will stop your activity, and pause it until you become un A.F.K
- Added MultiWarnUI - A new multi-type system, just like MultiBanUI and MultiMuteUI, but differs with functionality.
- Added /warn [player] - Warns a player. [player] is optional, and should only be used when offline.
  - Added /removewarn [player] - Removes the entire warning of a player. Soon, I plan to introduce a way so you don't have to remove the entire warning of a player. It'd also rely on warn points.
  
  ## What is Warn Points?
  Warn points, are essentially how many warns you give a player. We call it "Warn points" for short because it's just an easier way of saying it.
  
- Added /warns - Lists the players that have been warned.
- Added warnings information to /history [player] 3, which is also known as the warnings page
- Fixed internal server errors when using /history [player] 3 when the player was not found.
- Added Custom reasons tab to /mmute - This should only be used if the reason like "caps" is not on the muteable offenses list.
- Fixed Auto Sell not selling whole inventory when Auto sell Inventory feature is turned on.
- Fixed /sell inv only selling for $0.
