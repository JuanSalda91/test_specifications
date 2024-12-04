#Pseudocode

-- UNIT TEST --

1-Multiplication

Expectations of the function:

 - Expect multiplication(4, 6) to be equal to 24
 - Expect multiplication(-4, 6) to be equal to -24
 - Expect multiplication(0, 6) to be equal to 0
 - Unexpected multiplication("4", 6) to be an error
 - Unexpected multiplication(4) to be an error (missing an argument)

2-concatOdds

Example of the function "concatOdds ([7, 9, 5, 4, 3], [1, 9, 6, 8, 3, 5, 2])

Expectations of the function:

 - Expect concatOdds ([7, 9, 5, 4, 3], [1, 9, 6, 8, 3, 5, 2]) to be [1, 3, 5, 7, 9]
 - Expect concatOdds ([2, 4, 6]) to be []
 - Unexpected concatOdds ([1, 2, 3], "invalid") to be an error
 - Unexpected concatOdds(123, [1, 2, 3]) to be an error

 -- Functional Test --

 1- Shopping cart

  Guest Checkout:

 - When a user checks out as a guest, they should be prompted with an option to log in or create an account.
 - When a user checks out as a guest and does not create an account, they should proceed to checkout without being required to log in.

 Logged-In User Checkout:

 - When a logged-in user checks out, they should proceed directly to checkout without being prompted to log in.

 Cart Empty:

 - When a user attempts to check out with an empty cart, they should be shown an error stating that their cart is empty.

 Account Creation Prompt:

 - When a guest checks out, they should see a prompt asking if they want to create an account, with options to proceed as a guest.

Payment Process:

 - When a user proceeds to payment, they should see a summary of their cart items, subtotal, tax, and total.
 - When a user submits invalid payment details, they should see an error message and not proceed.

Confirmation:

 - When a user successfully completes a purchase, they should see a confirmation page with order details and a thank-you message.
 - When a guest completes a purchase, they should see an option to create an account after the confirmation.
