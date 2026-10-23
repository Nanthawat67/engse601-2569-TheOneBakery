# Test Case Draft — TheOneBakery

This is a draft based on current repository code and S1-B, not an official copy of the missing S2 worksheet. No test results are recorded here. See `S2-B_TheOneBakery.pdf`.

| TC | Purpose | Inputs / setup | Proposed expected result | Level |
|---|---|---|---|---|
| TC-01 | Correct order total | Two active products with known prices; valid quantities | server total equals price × quantity; order/items stored; initial status pending_review | Integration/API |
| TC-02 | Reject missing/inactive product | Empty items; unknown/inactive product | clear client error and no partial write | Integration/API |
| TC-03 | Quantity boundaries | 1, 0, -1, 1.5 in separate calls | accept 1; reject invalid values before write | Integration/API |
| TC-04 | Ingredient shortage | Recipe product; stock less than required | reject with details; no order/partial stock write | Integration |
| TC-05 | Role/state transition | Test users; skip state / disallowed role | reject; status/history unchanged | Integration/System |
| TC-06 | No double deduction | valid recipe stock; move to ready_for_packing; try duplicate | stock deducted once; one movement record; invalid repeat rejected | Integration |

All six cases: Not Executed as of this draft. Execute on isolated test database and update execution-report.md with real outputs.
