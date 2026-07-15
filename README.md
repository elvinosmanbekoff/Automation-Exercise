# Bug Report Example

## Bug Report

### Bug ID
BUG-001

### Title
User is able to enter card information that does not meet the required standards.

### Project
Online sales website

### Module
Checkout payment

### Environment

- Browser: Chrome 126
- OS: Windows 11
- Build: 1.0.8

### Severity
Critical

### Priority
High

### Preconditions

- User is logged in.
- Product is added to cart.

### Steps to Reproduce

1. Open the website.
2. Log in with valid credentials.
3. Add the first two models (RS.500 and RS.400).
4. Click on the Cart section.
5. Click the "Proceed to Checkout" button.
6. Click the "Place Order" button.
7. Enter the card information on the payment page.

   > Card name - A
   >
   > Card number - 1
   >
   > CVV - 1
   >
   > Expiration - 1
   >
   > Y - 1

8. Click "Pay and Confirm Order."

### Actual Result
The order is accepted even when the entered data does not meet the required standards.

### Expected Result
An error should be displayed when the entered data in the fields does not meet the required standards.

### Attachments

- Screenshot
- <img width="761" height="361" alt="image" src="https://github.com/user-attachments/assets/fcc2c941-f7c4-4546-b867-f6ae2b9b18fc" />


### Reproducibility
100% — reproduced 5/5 times.

### Status
Open
