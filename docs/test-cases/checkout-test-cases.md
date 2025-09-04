Checkout Test Cases
TC007_Checkout_Guest_Success

Title: Verify successful guest checkout
Preconditions: Item in cart
Steps:
Add item to cart.
Proceed to checkout as guest.
Enter valid shipping details.
Select payment method (e.g., PayPal).
Complete payment.


Expected Result: Order confirmation displayed.
Priority: High
Type: Functional
Risk Level: High
Requirement: US-301

TC008_Checkout_EmptyCart

Title: Verify checkout with empty cart
Preconditions: User on checkout page
Steps:
Navigate to checkout page without items in cart.
Attempt to proceed.


Expected Result: Error: "Cart is empty."
Priority: Medium
Type: Negative
Risk Level: Medium
Requirement: US-301

TC009_Checkout_SessionTimeout

Title: Verify checkout session timeout handling
Preconditions: Item in cart
Steps:
Add item to cart.
Proceed to checkout.
Wait for session timeout (e.g., 30 minutes).
Attempt to submit payment.


Expected Result: Session expired error, redirect to login.
Priority: Medium
Type: Negative
Risk Level: Medium
Requirement: US-302
