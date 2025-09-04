Payment Test Cases
TC004_Payment_CreditCard_Success

Title: Verify successful credit card payment
Preconditions: Valid credit card, user logged in
Steps:
Add item to cart.
Proceed to checkout.
Select credit card payment.
Enter valid card details (e.g., 4242-4242-4242-4242, expiry 12/26, CVV 123).
Submit payment.


Expected Result: Payment confirmation, order created.
Priority: Critical
Type: Functional
Risk Level: Critical
Requirement: US-201

TC005_Payment_InvalidCard

Title: Verify handling of invalid credit card
Preconditions: User logged in
Steps:
Add item to cart.
Proceed to checkout.
Select credit card payment.
Enter invalid card (e.g., 1234-1234-1234-1234).
Submit payment.


Expected Result: Error: "Invalid card number."
Priority: High
Type: Negative
Risk Level: High
Requirement: US-201

TC006_Payment_MaxAmount

Title: Verify payment with maximum transaction amount
Preconditions: User logged in
Steps:
Add items totaling maximum allowed amount (e.g., $10,000).
Proceed to checkout.
Select payment method.
Submit payment.


Expected Result: Payment processed or appropriate error.
Priority: Medium
Type: Edge Case
Risk Level: Medium
Requirement: US-202
