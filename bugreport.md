bugreport.md# Bug Reports – Online Grocery Delivery Application

## 1. Bug Reporting Overview

Project: Online Grocery Delivery Application

Testing Type: Manual Functional Testing

Purpose: Document software defects identified during QA testing.

Note: These are simulated defect examples for a learning portfolio. They have not been observed in a real application.

## 2. Bug Report Format

Each bug report includes:
- Bug ID
- Bug Title
- Environment
- Preconditions
- Steps to Reproduce
- Expected Result
- Actual Result
- Severity
- Priority
- Status

## 3. Bug Report 001 – Duplicate Email Registration

*Bug ID:* BUG-001

*Title:* Application allows registration with an existing email address.

*Module:* Customer Registration

*Environment:* Simulated test environment
*Precondition:* An account already exists with the email address.

*Steps to Reproduce:*
1. Open registration page.
2. Enter an email address already registered.
3. Enter valid details in other fields.
4. Click Register.

*Expected Result:* Application should reject duplicate email registration and display an appropriate error message.

*Actual Result:* Simulated example: Application allows duplicate registration.

*Severity:* High

*Priority:* High

*Status:* Open

## 4. Bug Report 002 – Invalid Login Accepted

*Bug ID:* BUG-002

*Title:* Application accepts an incorrect password during login.

*Module:* Customer Login

*Environment:* Simulated test environment

*Precondition:* A customer account exists.

*Steps to Reproduce:*
1. Open login page.
2. Enter registered email.
3. Enter an incorrect password.
4. Click Login.

*Expected Result:* Application should reject login and display an error message.

*Actual Result:* Simulated example: Customer is successfully logged in.

*Severity:* Critical

*Priority:* High

*Status:* Open

## 5. Bug Report 003 – Incorrect Cart Total

*Bug ID:* BUG-003

*Title:* Cart total does not update after increasing product quantity.

*Module:* Shopping Cart

*Environment:* Simulated test environment

*Precondition:* Customer has added a product to the cart.

*Steps to Reproduce:*
1. Open shopping cart.
2. Increase product quantity from 1 to 2.
3. Review the cart total.

*Expected Result:* Cart total should recalculate based on the updated quantity.

*Actual Result:* Simulated example: Cart total remains unchanged.

*Severity:* High

*Priority:* High

*Status:* Open

## 6. Bug Report 004 – Missing Validation Message

*Bug ID:* BUG-004

*Title:* Checkout allows customers to proceed without entering a delivery address.

*Module:* Checkout

*Environment:* Simulated test environment

*Precondition:* Customer has products in the shopping cart.

*Steps to Reproduce:*
1. Proceed to checkout.
2. Leave the delivery address empty.
3. Click Confirm Order.

*Expected Result:* Application should display a mandatory address validation message.

*Actual Result:* Simulated example: Order proceeds without an address.

*Severity:* High

*Priority:* High

*Status:* Open

## 7. Bug Report 005 – Incorrect Delivery Status

*Bug ID:* BUG-005

*Title:* Customer sees an incorrect delivery status after the driver updates the order.

*Module:* Delivery Tracking

*Environment:* Simulated test environment

*Precondition:* An order has been assigned to a delivery driver.

*Steps to Reproduce:*
1. Driver opens the assigned order.
2. Driver updates the status to Delivered.
3. Customer opens the order tracking page.

*Expected Result:* Customer should see the updated Delivered status.

*Actual Result:* Simulated example: Customer still sees Out for Delivery.

*Severity:* Medium

*Priority:* Medium

*Status:* Open

## 8. Bug Summary

| Bug ID | Module | Severity | Priority | Status |
|---|---|---|---|---|
| BUG-001 | Registration | High | High | Open |
| BUG-002 | Login | Critical | High | Open |
| BUG-003 | Shopping Cart | High | High | Open |
| BUG-004 | Checkout | High | High | Open |
| BUG-005 | Delivery Tracking | Medium | Medium | Open |

## 9. Severity vs Priority

Severity describes the impact of a defect on the application.

Priority describes how urgently the defect should be fixed.

Example:
- Critical severity: Unauthorized login is accepted.
- High priority: A defect affecting an important business function needs urgent attention.

## 10. Defect Life Cycle

New → Assigned → Open → Fixed → Retest → Verified → Closed

If the defect still exists after retesting, it can be reopened.

## 11. QA Responsibilities

- Identify and reproduce defects.
- Document clear reproduction steps.
- Assign appropriate severity and priority recommendations.
- Report defects to developers.
- Retest fixed defects.
- Perform regression testing.
- Verify and close resolved defects.

## 12. Project Note

These are simulated bug reports created for a self-directed QA learning portfolio. They are not defects discovered in a real application.
