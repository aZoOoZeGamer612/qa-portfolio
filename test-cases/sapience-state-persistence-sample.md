# Sample Test Case - Sapience NPC state persistence

> **Portfolio sample:** This is a testing scenario based on Sapience features. It is not a claim that this defect exists in the current public release.

**Area:** NPC memory / state persistence  
**Test type:** Functional + regression

## Objective
Verify that a villager's contextual state persists correctly through save/reload and that one-time behavior does not repeat incorrectly.

## Test steps
1. Trigger a contextual villager interaction.
2. Record the villager, location, relationship/state, and visible behavior.
3. Save and exit the world.
4. Reload the same save.
5. Revisit the same villager.
6. Observe whether the prior state persists correctly.
7. Repeat after a full game restart.
8. Repeat with another villager as a control.

## Expected result
Persistent state should survive reloads according to the feature's intended behavior, while one-time interactions should not incorrectly trigger again.

## Record during testing
- Minecraft / Sapience version
- Single-player or server
- Save used
- Reproduction rate
- Expected vs actual behavior
- Video or screenshots
- Relevant logs, if available
