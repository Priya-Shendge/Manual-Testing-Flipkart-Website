# Test Plan – Flipkart Website (Manual Testing)

## 1. Project Introduction
This test plan describes the manual testing approach for validating key
functional flows on the Flipkart e-commerce website, used here as a sample
System Under Test (SUT) for a QA portfolio project.

## 2. Objective
To identify defects and verify that the core shopping flows — search,
product browsing, cart, wishlist, and checkout — behave as expected from a
user's perspective.

## 3. Scope

### In Scope
- Login / Signup screen (UI validation, field validation)
- Product Search (valid, invalid, empty search)
- Filters & Sorting (price, brand, rating, discount)
- Product Listing Page (PLP) and Product Details Page (PDP)
- Add to Cart, Update Quantity, Remove from Cart
- Wishlist (Add / Remove)
- Checkout flow up to the payment method selection screen

### Out of Scope
- Real payment/transaction processing
- Backend, API, and database-level testing
- Load, performance, and security testing
- Mobile app testing (web only)

## 4. Test Approach
- **Type of testing:** Manual, Black-box, Functional & UI Testing
- **Technique:** Positive and negative test case design, boundary value checks
  on input fields (e.g., search box, pincode field, quantity selector)

## 5. Test Environment
| Item | Details |
|---|---|
| Application | www.flipkart.com |
| Browser(s) | Google Chrome (latest), Mozilla Firefox (latest) |
| OS | Windows 10/11 |
| Device | Desktop / Laptop (Web) |

## 6. Entry Criteria
- Application (website) is accessible and stable
- Test cases are written and reviewed
- Test data (sample search terms, dummy account details) is ready

## 7. Exit Criteria
- All planned test cases have been executed
- No open Critical/High severity defects blocking core flows
- Test summary report is prepared and shared

## 8. Roles
| Role | Responsibility |
|---|---|
| Priya Dadaso Shendge | Test case design, execution, bug reporting, summary reporting |

## 9. Deliverables
- Test Cases (`Test_Cases.xlsx`)
- Bug Report (`Bug_Report.xlsx`)
- Test Summary Report (`Test_Summary_Report.md`)
