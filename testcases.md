testcases.md
# Manual Test Cases – Online Grocery Delivery Application

## 1. Testing Overview

Project: Online Grocery Delivery Application

Testing Type: Manual Functional Testing

Testing Approach: Positive and Negative Testing

Test Environment: Simulated test environment

## 2. Test Case Format

Each test case includes:
- Test Case ID
- Feature
- Test Scenario
- Preconditions
- Test Steps
- Expected Result
- Actual Result
- ## 3. Customer Registration Test Cases

### TC-001: Register with valid details
*Precondition:* Customer is on the registration page.

Steps:
1. Enter a valid name.
2. Enter a valid email.
3. Enter a valid password.
4. Click Register.

Expected Result: Customer account should be created successfully.

Actual Result: Not executed.

Status: Not Run.

### TC-002: Register with invalid email
Steps:
1. Open registration page.
2. Enter an invalid email format.
3. Complete other mandatory fields.
4. Click Register.

Expected Result: Appropriate email validation message should appear.

Actual Result: Not executedStatus
Status: Not Run.

### TC-003: Register with empty mandatory fields
Steps:
1. Open registration page.
2. Leave mandatory fields empty.
3. Click Register.

Expected Result: Validation messages should appear for mandatory fields.

Actual Result: Not executed.

Status: Not Run.

## 4. Customer Login Test Cases

### TC-004: Login with valid credentials
Steps:
1. Open login page.
2. Enter registered email.
3. Enter correct password.
4. Click Login.

Expected Result: Customer should successfully log in.

Actual Result: Not executed.
Status: Not Run.

### TC-005: Login with incorrect password
Steps:
1. Enter registered email.
2. Enter incorrect password.
3. Click Login.

Expected Result: Login should be rejected with an appropriate error message.

Actual Result: Not executed.

Status: Not Run.

### TC-006: Login with empty fields
Steps:
1. Open login page.
2. Leave email and password empty.
3. Click Login.

Expected Result: Required field validation should be displayed.

Actual Result: Not executed.

Status: Not Run.
## 5. Product Browsing Test Cases

### TC-007: View available products
Steps:
1. Log in as a customer.
2. Navigate to product listing.
3. Review displayed products.

Expected Result: Available products should display correct names and prices.

Actual Result: Not executed.

Status: Not Run.

### TC-008: Search for an existing product
Steps:
1. Open product search.
2. Enter a valid product name.
3. Click Search.

Expected Result: Relevant matching products should appear.

Actual Result: Not executed.

Status: Not Run.

### TC-009: Search for a non-existing product
Steps:
1. Enter a product name that does not exist.
2. Click Search.

Expected Result: A suitable no-results message should appear.

Actual Result: Not executed.

Status: Not Run.

## 6. Shopping Cart Test Cases

### TC-010: Add product to cart
Steps:
1. Open product listing.
2. Select an available product.
3. Click Add to Cart.

Expected Result: Product should appear in the shopping cart.

Actual Result: Not executed.

Status: Not Run.

### TC-011: Update product quantity
Steps:
1. Add a product to the cart.
2. Increase its quantity.
3. Review the cart total.

Expected Result: Quantity and cart total should update correctly.

Actual Result: Not executed.

Status: Not Run.

### TC-012: Remove product from cart
Steps:
1. Add a product to the cart.
2. Click Remove.
3. Review the cart.

Expected Result: Selected product should be removed.

Actual Result: Not executed.

Status: Not Run.

## 7. Checkout Test Cases

### TC-013: Checkout with valid address
Steps:
### TC-013: Checkout with valid address
Steps:
1. Add products to cart.
2. Proceed to checkout.
3. Enter a valid delivery address.
4. Confirm the order.

Expected Result: Order should be successfully placed.

Actual Result: Not executed.

Status: Not Run.

### TC-014: Checkout with missing address
Steps:
1. Add products to cart.
2. Proceed to checkout.
3. Leave delivery address empty.
4. Attempt to confirm order.

Expected Result: Address validation message should appear.

Actual Result: Not executed.

Status: Not Run.

### TC-015: Verify order total
Steps:
1. Add multiple products to cart.
2. Proceed to checkout.
3. Review the order summary.

Expected Result: Order total should accurately reflect item prices, quantities, and applicable charges.

Actual Result: Not executed.

Status: Not Run.

## 8. Test Execution Summary

| Metric | Value |
|---|---|
| Total Test Cases | 15 |
| Passed | 0 |
| Failed | 0 |
| Blocked | 0 |
| Not Run | 15 |

Note: All test cases are documented but not executed against a live application.

## 9. Testing Conclusion

The test cases cover important functional areas of the online grocery delivery application. Actual execution will be performed when a test application and environment are available.

## 10. Project Note

This is a self-directed QA portfolio simulation. The test cases are designed for learning and have not been executed against a real application.
