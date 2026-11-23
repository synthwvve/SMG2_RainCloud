This works with Super Mario Galaxy 2 (SB4E01). This has not been tested on other regions.

### Setup
There is particles, effects, and a particle texture included with the module. All three of these can be added to your `Effect.arc` with the use of [Pygapa](https://github.com/AwesomeTMC/pygapa)

### Configuration
The configuration is the same as SMG1

Obj_arg0: Rain/Shadow Length: Sets the rain length. This also sets the shadow drop length. Default is 1000. No rain will appear if Obj_arg3 is set.  
Obj_arg3: Is not Raining?: If set, the cloud will be white, and no rain will fall from the cloud.

**Path ID**<br>
A valid one is required for this to work properly; the Path ID refers to the identifier assigned to a movement path in the level editor, and you can obtain or set it by selecting the desired path and noting its assigned ID value.<br><br>
 **SW_A**<br>
When activated, the Eye Beamer will go from its waiting state to its patrolling state.<br><br>
**Cutscene ID / Cast ID**<br>
Whether this object can take part in a cutscene.
