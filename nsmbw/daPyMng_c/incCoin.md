## `void daPyMng_c::incCoin(int playerID)`
### `0x80060250`
Awards the player a shiny coin... without them actually having to collect one. This function also manages the maximum number of coins, so it may be run when the player collects a physical coin, too.
### Parameters
1. **playerID**: The player that got the coin. This value seems to do nothing at all. (view comments)

### Comments
This function cannot award the player multiple coins; you need to use a for loop.<br>
The function uses `playerID` to run [`FUN_80060170`](FUN_80060170.md) on that player.

