# Project Profile — ENGSE212 × ENGSE601

| Field | Verified information |
|---|---|
| Project Thai name | ระบบสั่งซื้อและบริหารจัดการร้านเบเกอรี่ THE ONE Bakery |
| Project English name | THE ONE Bakery Ordering and Management System |
| TeamName | `TheOneBakery` |
| Critical feature selected in supplied S1-B | การบันทึกคำสั่งซื้อและคำนวณยอดรวม |
| Problem context | The supplied worksheet identifies recording an order and calculating its total correctly as the selected feature. The public source repository contains an order API, product-price lookup, `orders`, `order_items`, status history and recipe/inventory logic. |
| Main code source | https://github.com/Nanthawat67/the-one-bakery-New (`main`; exact commit to pin before Release) |
| Course evidence repository | https://github.com/Nanthawat67/engse601-2569-TheOneBakery |
| Static code paths reviewed | `routes/orders.js`, `routes/production.js`, `middleware/auth.js`, `database/schema.sql`, `README-FIX12.md`, `tests/basic.test.js` |
| Formal Proposal / approved SRS | **Not Ready** — not present in the checked evidence pack; no official requirement IDs have been inferred. |
| Approved bakery HLD / design | **Not Ready** — a source-code component flow is shown as retrospective, not claimed to be a pre-existing design document. |
| Actual application API/DB/System/UAT results | Not available from the preparation workspace; see `03-test-execution/execution-report.md`. |
| Stakeholder decisions / sign-off | Not available in the checked source pack; do not claim formal approval. |

## Key open questions

1. Which approved Proposal/SRS version is the source of truth, and who confirms the requirement IDs and acceptance criteria?
2. What exact quantity types and error responses are required for invalid input?
3. What authorization/ownership rule must protect cancellation?
4. Which active products have recipes, and are recipe quantities and inventory units consistent?
5. Which source commit represents the current implementation under review?

## Boundary of this profile

The project evidence pack describes the THE ONE Bakery project. The W05 course exercise separately uses Case X with SRS v1.1 and HLD v0.9, as directed by the current ENGSE601 materials. Do not treat W05 Case X components as design facts about THE ONE Bakery.
