## `void daPyMng_c::addScore(int score, int playerID)`
### `0x80060690`
Awards the player(s) score.
### Parameters
1. **score**: Amount of score the players will earn.
2. **playerID**: The player that receives the score. Does pretty much nothing, like the one in [`incCoin`](incCoin.md).

### Comments
As with [`incCoin`](incCoin.md), this function uses the player ID as the parameter for `FUN_80060170`. 
