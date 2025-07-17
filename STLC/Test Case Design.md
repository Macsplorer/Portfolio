# ***Test Case Design for New Features***

**Feature 1: Product rating System**

---

**Test Case 1:** Logged in users can leave a star rating and a review.

- **Objective:** Make sure logged in customer can leave a rating and a review.
- **Test Steps:**
1. Log in and go to product page.
2. Click on number of stars up to 5 stars and leave a written review.
3. Click submit.
- **Expected Outcome:** You will see the rating saved below the product you rated along with your review.

**Test Case 2:** Guest can view ratings, but not add a rating.

- **Objective: Verify only members can leave ratings.** 
- **Test Steps:**
1. Log out.
2. Visit a product page.
3. View ratings.
- **Expected Outcome:** The website will not allow guest to add review.

**Test case 3: Leave a review without a purchase.**

- **Objective: Try and leave a review without purchasing the product.**
- **Test Steps:**
1. Try to leave a review without purchasing product.
2. Log into account
3. Click on a product and leave a review without buying.
- **Expected Outcome:** You will not be able to leave a review unless you purchase an item.

---

**Feature 2:** Age Verification on alcohol.

2. Age Check for alcohol products


**Test case 1:** Enter age over 18 
**Test Steps:**
1. Type age
2. You can see the alcohol products.

**Test case 2:** Logged in adult can skip pop up.
**Test steps:**
1. Login in with age verification account.
2. Go to alcohol product.
3. No age check pop up.

**Test case 3:** Try to go to product URL directly.
**Test Steps**
1. Got directly to product URL.
2. Paste alcohol product link in browser.
3. It blocks or redirects you.

---

**Feature 3:** Changes to Shipping Cost

3. Shipping Cost Changes


**Test case 1:** Add cheap items under €20  
**Test Steps**
1. Add less than €20 worth of items.
2. Go to checkout.
3. Shipping shows a flat rate of €5.

**Test case 2:** Add items over €20+
**Test Steps**
1. Add €20 worth of items or more.
2. Go to checkout.
3. Shipping is free

---
