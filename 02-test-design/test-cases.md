# S2-B Test Case Set — TheOneBakery

**Feature:** POST `/api/orders` — record order and calculate total.

**Requirement basis:** The team S1-B states that an order must be recorded and its total calculated correctly. No approved Proposal/SRS ID/version was found in the checked repo. `AC-ORD-01` through `AC-ORD-04` in the S2-B PDF are temporary proposed acceptance criteria, not official SRS IDs. Confirm with the requirement owner.

| TC | Technique | Test data / setup | Expected result (proposed) | Level | Status |
|---|---|---|---|---|---|
| TC-01 | EP: valid | One active product; quantity 1; known database price | Order, item and `pending_review` history recorded; total equals server price | Integration/API | Not Executed |
| TC-02 | EP: valid multi-item | Two active products; quantities 1 and 2 | Total equals sum of server prices × quantities; rows match submitted items | Integration/API | Not Executed |
| TC-03 | EP: missing input | Missing customer field or empty `items` in separate requests | 4xx and no order/item rows; route currently returns 400 for these required-field cases | Integration/API | Not Executed |
| TC-04 | BVA | quantity 1, 0 and -1 in separate requests | 1 may be accepted if rest valid; 0/-1 rejected before write; record actual status because current catch path may return 500 | Integration/API | Not Executed |
| TC-05 | BVA/type partition | quantity 1.5 | Reject as invalid input; no write; schema quantity is INT but route does not show explicit integer validation | Integration/API | Not Executed |
| TC-06 | EP: invalid product | unknown and inactive product IDs in separate requests | Reject with no partial rows; invalid-product path may currently return generic 500 | Integration/API | Not Executed |
| TC-07 | Decision table: active × stock | active product with sufficient vs insufficient recipe stock | sufficient => create; insufficient => resource error (code path uses 409) and no partial order/items | Integration/API | Not Executed |
| TC-08 | Transaction / rollback | Multi-item order where a later item is invalid or under-stocked | Whole request rejected with no partial order/item writes | Integration | Not Executed |

Never put Pass/Fail or actual observations into this design file. Put actual results in `03-test-execution/execution-report.md` and link real evidence files. Use isolated test data and never expose credentials or real customer data in this Public repo.
