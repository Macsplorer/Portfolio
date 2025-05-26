
Folder for New Features & Critical Questions
1. Product Rating System
Requirement: Users should be able to rate products with a 5-star system and add written feedback.

Critical Testing Questions:

Can all users (logged-in and guest) see the product ratings and reviews?

Is the rating feature restricted to only users who have purchased the product?

What happens if a user submits an empty review or only a star rating without written feedback—does the system handle this gracefully?

2. Age Verification for Alcoholic Products
Requirement: A modal should appear asking if the user is 18+ before accessing alcoholic products.

Critical Testing Questions:

Does the age verification modal appear every time a user tries to access alcoholic products, or is it shown only once per session?

What happens if a user enters an invalid age (e.g., letters, empty field, or age under 18)?

Can the user bypass the modal through the browser’s back button, refresh, or other navigation tricks?

3. Shipping Cost Changes
Requirement: Orders above a certain amount get free shipping, while others incur a fee.

Critical Testing Questions:

Is the shipping cost correctly calculated and updated in real-time as users add/remove products from the cart?

Is the threshold amount for free shipping clearly displayed to the user during the checkout process?

Are edge cases handled correctly—for example, what happens if the total is exactly at the free shipping threshold?
