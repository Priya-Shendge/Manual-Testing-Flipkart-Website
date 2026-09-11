# Test Summary Report – Flipkart Website (Manual Testing)

## Project
Manual Testing – Flipkart Website (Sample QA Project)

## Tester
Priya Dadaso Shendge

## Test Execution Summary
| Metric | Count |
|---|---|
| Total Test Cases | 20 |
| Passed | 2 |
| Failed | 0 |
| Not Executed | 18 |
| Total Bugs Logged | 5 |
| Critical / High Bugs | 0 |
| Medium Bugs | 3 |
| Low Bugs | 2 |

> Note: This sample project ships with 2 test cases executed as a working
> example (`TC_001`, `TC_002` in `Test_Cases.xlsx`). The remaining cases are
> ready to execute — update the **Actual Result** and **Status** columns as
> each one is run.

## Module-wise Coverage
| Module | Test Cases |
|---|---|
| Login/Signup | 3 |
| Search | 3 |
| Filters | 3 |
| Product Listing | 1 |
| Product Details | 2 |
| Cart | 3 |
| Wishlist | 2 |
| Checkout | 3 |

## Observations
- Core flows (search, cart, wishlist, checkout entry) are functionally
  usable end-to-end.
- Most issues found were **Low–Medium severity UI/UX gaps** (e.g., filters
  resetting on back-navigation, delayed cart count updates) rather than
  blocking functional failures.
- No Critical or High severity defects were found that block a user from
  completing a purchase flow.

## Conclusion
The tested flows on the Flipkart website behave largely as expected from a
user's perspective. All logged bugs and their reproduction steps are
available in `Bug_Report.xlsx`. Detailed test case results are available in
`Test_Cases.xlsx`.
