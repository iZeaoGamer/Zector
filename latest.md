## V10.2; Minor

- Fixed charity enchant turning tokens into zeros. (Was due to a typo made in the code. Whoopsies!)
- Downgraded the server to 20 players due to possible server crashes. (Still unknown)
- Cleaned up /mban UI codes!
- Temp Ban Time now caculates properly when broadcasted.
- Added /history; Allows you to check for a player's case information.
- Added Banned Date & Unban Date to /history command informative on a player.
- Fixed issues raised to do with temp ban option being set to the wrong value in /history.
- Type /history <player> 1 for bans information on a player, and /history <player> 2 for mutes information on a player.
- Removed a lot of blank lines within the bans code.
- Fixed commands not working whilst muted
- Fixed players being able to use certain commands whilst in combat.
- Added new information: Ban types to /history <player> 1.
- Added new information: Mute types to /history <player> 2.
- Fixed Slient Ban / silent mute not working due to the server being broadcasted once a ban or mute has commenced even if they have turned on silent ban or silent mute.
- Fixed showing wrong information when using /history <player>
- Clean-up almost duplicated codes, and just added it as a one code which runs, instead of reoccurring a lot of the same codes being ran at once.
- Fixed #server-logs chat from spamming with ban / mute types the sender had given him, but instead, it will say on the same text message, with commas to seperate the ban types, just like the reasons seperation that is on the same message.
- Added new functions: getBanTypes(), setBanTypes(), addBanTypes(), and removeBanTypes().
  
getBanTypes(): Returns the full ban types, in commas and strings. Returns empty if no ban types are valid. This is also the same as getMuteTypes().

setBanTypes(): Sets the ban type specificed. This is also the same as setMuteTypes().

addBanTypes(): Adds onto the ban type, in commas, and plussing onto the other validable ban types. This is also the same as addMuteTypes().

removeBanTypes(): Removes all of the ban types from the given ban. This is so ban types don't start duplicating onto the next ban. This is also the same as removeMuteTypes().

- Fixed Creepers from stacking, making it harder for raids.
- Creepers no longer stack. Other mobs however, do stack.
