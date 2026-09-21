# PSP-OT2-001 - UI text renders behind background layers

**Project:** Experimental Oregon Trail II PSP build  
**Type:** UI / Rendering  
**Environment:** Physical PSP hardware  
**Build:** Experimental build; exact revision was not recorded  
**Severity:** Major  
**Reproduction rate:** Observed immediately during testing; exact repeated count was not recorded

## Summary
Text and UI elements were rendered in the wrong layer order. Some text appeared behind background elements, and some text became visible only after player input.

## Steps to reproduce
1. Start the build on physical PSP hardware.
2. Enter the first visible menu or gameplay UI.
3. Observe text placement relative to background panels.
4. Navigate or provide controller input.
5. Observe whether previously hidden text becomes visible.

## Expected result
UI text should render above its background layer and remain visible regardless of whether the player is providing input.

## Actual result
- Text appeared behind background elements.
- Layer ordering appeared reversed or incorrect.
- Some text became visible only after input.
- The interface was difficult to read.

## Impact
Important interface information could become difficult or impossible to read.

## Retest / regression plan
- Verify draw order on menus and gameplay screens.
- Compare the same build on PPSSPP and physical PSP hardware.
- Retest affected screens after a fix.
- Regression-check text boxes, backgrounds, menus, and input overlays.
