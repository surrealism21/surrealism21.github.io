## `bool daPyMng_c::playerCheck(int * playerID)`
### `0x80060170`
This checks if the player is Mario / Luigi / a playable Toad and returns zero if it is. It is *probably* in `daPyMng_c`.

### Parameters
1. **playerID integer pointer**: This is a pointer to a player ID that is always provided to this function by functions like [`incCoin`](incCoin.md) and [`addScore`](addScore.md).

### References
`80060274` - Call in `incCoin` to set a local bool<br>
`800606d0` - Call in `addScore` to set a local bool

### Comments / Possible function?
This is a odd function. It appears to return false if the player ID it gets is Toad, (Likely the Toad Needs Help one).
I will soon document the score and coin related functions in `dMultiMng_c` and explain here why this may exist. For now, toodles!
