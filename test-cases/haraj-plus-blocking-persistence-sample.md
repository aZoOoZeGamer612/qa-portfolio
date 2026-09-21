# Sample Test Case - Haraj Plus seller blocking and sorting persistence

> **Portfolio sample:** This is a testing scenario based on Haraj Plus features. It is not a claim that this defect exists in the current public release.

**Area:** Seller blocking / sorting / stored preferences  
**Test type:** Functional + compatibility + persistence

## Objective
Verify that blocked sellers remain hidden when the user changes sorting, refreshes the page, and restarts the browser.

## Test steps
1. Open a results page.
2. Block one seller.
3. Confirm that seller's listings disappear.
4. Change the result sort order.
5. Confirm the blocked seller remains hidden.
6. Refresh the page.
7. Confirm the blocked seller remains hidden.
8. Close and reopen the browser.
9. Return to the same results/search area.
10. Confirm the block preference persists.
11. Repeat in Firefox and Chrome.

## Expected result
The blocked seller should remain hidden through sorting, refresh, and browser restart unless the user explicitly removes the block.
