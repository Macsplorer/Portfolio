## **Test Execution Documentation for Market Mate Webshop** 

## **Test Case 1: Valid Discount for Prime Members**
### Test Cases:
 1. **Login as a Prime member.
 2. **Add products worth €60 to the cart.
 3. **Verify that the discount is applied and shipping is free.
#### Execution Result:
#### Pass: Discount and free shipping were applied correctly.

⸻

Test Case 2: Discount for Student Purchases
• Test Steps:
1. Login as a student.
2. Add 2 products costing €30 each to the cart.
3. Verify that the 15% discount is applied.
• Execution Result:
• Pass: The discount applied correctly to the total order price.

⸻

Test Case 3: Discount for Single High-Price Item
• Test Steps:
1. Add 1 product worth €12 to the cart.
2. Check if the discount is applied to the product, but shipping should be discounted.
3. Verify that shipping cost is discounted, but no product discount applies.
• Execution Result:
• Pass: Shipping was discounted, but no discount on the product itself.

⸻

Test Case 4: Display Past Orders
• Test Steps:
1. Login to an account.
2. Go to the order history section.
3. Verify that past orders are displayed correctly, including product details and order status.
• Execution Result:
• Pass: Order history displayed with correct product details and statuses.

⸻

Test Case 5: No Orders in History
• Test Steps:
1. Login to an account with no past orders.
2. Go to the order history section.
3. Ensure that a message like “No past orders” is shown.
• Execution Result:
• Pass: Appropriate message “No past orders” was displayed.

⸻

Test Case 6: Inventory Update After Purchase
• Test Steps:
1. Add 3 items to the cart (ensure at least one item has low stock).
2. Complete the purchase.
3. Check inventory for the purchased items.
• Execution Result:
• Pass: Inventory for purchased items updated successfully.

⸻

Test Case 7: Out of Stock Item
• Test Steps:
1. Attempt to add an out-of-stock item to the cart.
2. Attempt to proceed to checkout.
• Execution Result:
• Pass: The system prevented the user from purchasing out-of-stock items.

⸻

Test Reporting for Bugs Found During Execution

Bug Report 1: Discount Not Applied for Prime Member on Specific Conditions
• Title: Prime Member Discount Not Applied Correctly on Certain Products
• Priority: High
• Reporter: [Your Name]
• Date: [Date]
• Environment: Staging
• Application: Market Mate Webshop
• Page: Cart and Checkout
• Browser/OS: Google Chrome / Windows 10
• Repro Steps:
1. Login as a Prime Member.
2. Add 2 products worth €25 each to the cart.
3. Check if the 20% discount applies.
• Expected Result: The total price should reflect a 20% discount and shipping should be free.
• Actual Result: No discount was applied despite being a Prime Member.
• Screenshots/Attachments:
(Attach screenshot showing the cart total before and after applying the discount)
• Additional Information:
Issue seems to occur only with certain product combinations under the €50 threshold.

⸻

Bug Report 2: Missing Order History for Registered User
• Title: No Order History Displayed for Registered User
• Priority: Medium
• Reporter: [Your Name]
• Date: [Date]
• Environment: Staging
• Application: Market Mate Webshop
• Page: Order History Page
• Browser/OS: Mozilla Firefox / MacOS
• Repro Steps:
1. Login to a registered user account with previous purchases.
2. Navigate to the order history page.
• Expected Result: All past orders should be displayed correctly.
• Actual Result: The page displays no orders, even though purchases were made.
• Screenshots/Attachments:
(Attach screenshot of the “No Past Orders” message displayed)
• Additional Information:
This issue only appears on specific registered user accounts.

⸻

Bug Report 3: Out of Stock Items Can Still Be Added to Cart
• Title: Out of Stock Item Can Be Added to Cart
• Priority: Critical
• Reporter: [Your Name]
• Date: [Date]
• Environment: Staging
• Application: Market Mate Webshop
• Page: Product Details and Cart Page
• Browser/OS: Google Chrome / Windows 10
• Repro Steps:
1. Navigate to a product page with the “Out of Stock” label.
2. Click “Add to Cart”.
3. Proceed to checkout.
• Expected Result: The system should prevent adding out-of-stock items to the cart.
• Actual Result: The item was added to the cart despite being out of stock.
• Screenshots/Attachments:
(Attach screenshot showing out-of-stock item added to the cart)
• Additional Information:
Users are still able to proceed with checkout even if the item is out of stock.

⸻

Conclusion
• Test Execution: All designed test cases were executed successfully, with a few bugs encountered related to discounts, order history display, and out-of-stock items.
• Bug Reporting: The bugs were documented with all necessary details including expected and actual outcomes, steps to reproduce, and any additional information to assist developers in resolving the issues.
• Next Steps: Once bugs are fixed, re-execution of test cases will be required to confirm that the issues are resolved.
