# GroceryMate Test Execution

This file shows what happened when we tested the 3 new features on the GroceryMate website.

Website: https://grocerymate.masterschool.com/

---

## 1. Product Rating System

**TC1:** Logged-in user gives star rating and review. 
Passed — Both rating and review showed up

**TC2:** Logged-in user who didn’t buy tries to rate  
Passed — Rating was not allowed

**TC3:** Guest user looks at ratings  
Passed — Can see ratings, but can’t add one

---

## 2. Age Check for Alcohol Products

**TC1:** Enters age over 18  
Passed — Product became visible

**TC2:** Logged-in adult user visits alcohol product  
Passed — No popup, product shows

**TC3:** Tries to open alcohol product with direct link  
Failed — Page not blocked or redirected

---

## 3. Shipping Cost Changes

**TC1:** Cart under €20  
Passed — Shipping fee was added

**TC2:** Cart over €20  
Passed — Free shipping applied


---

## Summary

- Total Tests: 8 
- Passed: 7  
- Failed: 1  

---
