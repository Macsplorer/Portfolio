# ***Test Case Design for New Features***

**Feature 1: Discount System**

**Test Case 1: Valid Discount for Prime Members**

- **Objective:** Ensure discounts apply correctly for Prime Members.
- **Test Steps:**
1. Log in as a Prime member.
2. Add products worth €60 to the cart.
3. Verify that the discount and free shipping are applied.
- **Expected Outcome:** Total discount and free shipping should apply correctly.
- **Test Design Technique:** Boundary Value Analysis (for testing price thresholds)

**Test Case 2: Discount for Student Purchases**

- **Objective:** Verify student discount applies to purchases above €25 with fewer than 3 items.
- **Test Steps:**
1. Log in as a student.
2. Add 2 products costing €30 each to the cart.
3. Verify discount application.
- **Expected Outcome:** 15% discount on total order price.
- **Test Design Technique:** Equivalence Partitioning

**Test Case 3: Discount for Single High-Price Item**

- **Objective:** Verify that single high-priced items receive shipping discount only.
- **Test Steps:**
1. Add 1 product worth €12 to the cart.
2. Verify shipping discount applies but product discount does not.
- **Expected Outcome:** Shipping should be discounted, with no discount on the product.
- **Test Design Technique:** Decision Table Testing

**Feature 2: Order History**

**Test Case 1: Display Past Orders**

- **Objective:** Ensure order history displays correct details for logged-in users.
- **Test Steps:**
1. Log in to an account.
2. Navigate to order history section.
3. Verify past orders show correct product details and status.
- **Expected Outcome:** All past orders display with accurate information.
- **Test Design Technique:** State Transition Testing

**Test Case 2: No Orders in History**

- **Objective:** Verify display when user has no past orders.
- **Test Steps:**
1. Log in to an account with no past orders.
2. Navigate to order history section.
3. Verify "No past orders" message appears.
- **Expected Outcome:** Appropriate message displays.
- **Test Design Technique:** Boundary Value Analysis

**Feature 3: Real-Time Inventory Updates**

**Test Case 1: Inventory Update After Purchase**

- **Objective:** Verify inventory decreases after purchase completion.
- **Test Steps:**
1. Add 3 items to cart (include one low-stock item).
2. Complete purchase.
3. Check inventory of purchased items.
- **Expected Outcome:** Inventory updates for purchased items.
- **Test Design Technique:** Regression Testing

**Test Case 2: Out of Stock Item**

- **Objective:** Ensure out-of-stock items cannot be purchased.
- **Test Steps:**
1. Attempt to add an out-of-stock item to cart.
2. Attempt to proceed to checkout.
- **Expected Outcome:** System prevents purchase of out-of-stock items.
- **Test Design Technique:** Boundary Value Analysis

**Test Automation**

The following test cases will be automated:

1. **Discount System** – Automate discount verification for Prime members, students, and single-item purchases.
2. **Order History** – Automate past order display checks and empty history scenarios.
3. **Inventory Updates** – Automate post-purchase inventory updates and out-of-stock purchase prevention.

Automation will reduce testing time for repetitive tests across discount, inventory, and order history features.
