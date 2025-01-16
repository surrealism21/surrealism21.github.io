## `void daPlBase_c::playSound(daPlBase_c *this, SFX sfx, long shouldPlay)`
### `80057e70` 
This function plays sounds originating from the player. It can play any sound.
### Parameters
1. **daPlBase_c pointer**: A pointer to a `daPlBase_c` class. This is generally just a pointer to the player actor that runs the function.
2. **SFX sfx**: A sound effect enum
3. **long shouldPlay**: Just set this to zero if you want your sound to play.

### References
This function is called by the player. Here are the callings I understand.<br>
**Jumping related**<br>
`801460e8` - Small Mario jumping<br>
`80146108` - Mini Mario jumping<br>
`80146128` - Big Mario+ jumping<br>
`80146154` - Small Mario sustain jumping<br>
`80146168` - Mini Mario sustain jumping<br>
`8014617c` - Big Mario+ sustain jumping<br>
**Vine Related**<br>
`80132ef0` - Moving on a vine
To determine the jump number of the player in a triple jump, it is taken from `dAcPy_c`.