# PSP-OT2-001 - UI text renders behind background layers

**Project:** Experimental Oregon Trail II PSP build  
**Type:** UI / Rendering  
**Environment:** Physical PSP hardware  
**Build:** Experimental build; exact revision was not recorded  
**Severity:** Major  
**Reproduction rate:** Observed immediately during testing; exact repeated count was not recorded

## Summary
Text and UI elements were rendered in the wrong layer order. Some text appeared behind background elements, and some text became visible only after player input.

## Preconditions
1. Experimental Oregon Trail II PSP build installed on the device.
2. Launch the game normally.

## Steps to reproduce
1. Start the build on physical PSP hardware.
2. Enter the first visible menu/gameplay UI.
3. Observe text placement relative to background panels.
4. Navigate or provide controller input.
5. Observe whether previously hidden text becomes visible.

## Expected result
UI text should render above its background layer and remain visible regardless of whether the player is currently providing input.

## Actual result
- Text appeared behind background elements in parts of the UI.
- Layer ordering appeared reversed or incorrect.
- Some text was only visible after input.
- The UI was difficult to read within the first few seconds of testing.

## Impact
The issue did not merely affect appearance. It made important UI information difficult or impossible to read, blocking reliable use of parts of the interface.

## Evidence
The original testing session was not preserved as a formal QA report, so this reconstructed portfolio report does not claim screenshots, logs, or exact build metadata that were not recorded.

## Follow-up / retest plan
- Verify draw order on every menu and gameplay screen.
- Test before and after controller input.
- Test transitions between screens.
- Compare the same build on PPSSPP and physical PSP hardware.
- Retest the affected screens after any rendering-layer fix.
- Run a short regression pass on text boxes, backgrounds, menus, and input overlays.
