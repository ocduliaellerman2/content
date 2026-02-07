# Article Outline: How to Hide COD for Guest Customers in Shopify?

**Author:** Ferb
**App:** Hide, Sort, Rename Payment Methods
**Topic:** Hiding Cash on Delivery (COD) for Guest Users to reduce RTO.
**Target Word Count:** 1500-2000 words

---

## Meta Data
- **Title:** How to Hide COD for Guest Customers in Shopify? | Reduce RTO
- **Meta Description:** Learn how to easily hide Cash on Delivery (COD) for guest customers in your Shopify store using the "Hide, Sort, Rename Payment Methods" app. Reduce return rates and encourage prepaid orders.
- **Slug:** `how-to-hide-cod-guest-customers-shopify`
- **Keywords:** hide cod shopify, disable cash on delivery guest checkout, shopify payment rules, reduce rto shopify, hide payment methods app

---

## Outline Structure

### 1. Introduction
- **Hook:** The challenge of high RTO (Return to Origin) rates on Cash on Delivery (COD) orders, especially from unverified guest users (often exceeding 40%).
- **Problem:** Guest checkout is convenient but risky for COD. Users may place orders with fake details or simply refuse delivery.
- **Solution:** Restricting COD to logged-in/verified customers only.
- **Tool:** Introduce the "Hide, Sort, Rename Payment Methods" app as the easy solution.

### 2. Understanding Guest Checkout & RTO Risks
- **What is Guest Checkout:** Explained for merchants. Quick, no-account purchase.
- **The Risk:** Lack of accountability. No order history. Guest COD orders often see **35-50% RTO** vs 10-15% for logged-in customers.
- **The Cost:** Shipping fees + Reverse logistics + Damaged goods (estimated ₹80-150 loss per RTO).
- **Why Hide COD:** Filter out non-serious buyers, encourage account creation (higher LTV).

### 3. Prerequisites
- Shopify Store (obviously).
- "Hide, Sort, Rename Payment Methods" app installed.
- Cash on Delivery (COD) enabled in Payment settings.

### 4. Step-by-Step Guide: Hiding COD for Guests
*(Screenshots required for each step)*
- **Step 1: Install the App:** Search for "Hide, Sort, Rename Payment Methods" on Shopify App Store.
- **Step 2: Access the Dashboard:** Open the app from Shopify Admin.
- **Step 3: Create a New "Hide" Rule:** Click "Create Rule" -> "Hide Payment Methods".
- **Step 4: Select Payment Method:** Choose "Cash on Delivery" (or custom manual payment).
- **Step 5: Define the Condition:**
    - **Condition Type:** Customer / Customer Tag.
    - **Logic:** `IF Customer is Guest THEN Hide` (or `IF NOT Logged In`).
    - *Screenshot focus:* The exact condition selector in the app.
- **Step 6: Save and Activate:** Toggle the rule status to Active.
- **Step 7: Testing:** Go to checkout in Incognito mode (Guest) -> Check COD is hidden. Log in -> Check COD is visible.

### 5. Alternative Approaches (Advanced)
- **Hide by Tag:** Hide COD for customers tagged "Bad Buyer".
- **Hide by Cart Value:** Hide COD for Guests if Order < $10 or > $500.
- **Hide by Product:** Restrict COD for high-risk items for guests only.

### 6. Best Practices
- **Communication:** Add a message on the cart page: "Login to unlock Cash on Delivery".
- **Incentives:** "Sign up for COD + 5% Off".
- **Don't Block Everything:** Ensure prepaid options (Card, PayPal) are always visible for guests.

### 7. Troubleshooting
- **Rule not working:** Check if other rules are conflicting.
- **Payment still showing:** Clear browser cache or test in Incognito.
- **Customer Tag delays:** Shopify tags sometimes take a few minutes to sync (though guest status is instant).

### 8. FAQ
- **Q:** Can I hide COD only for specific countries? (A: Yes, the app supports geolocation).
- **Q:** Will this affect my existing customers? (A: No, logged-in users are unaffected).
- **Q:** Does it work on Shopify Plus? (A: Yes, compatible with checkout extensibility).
- **Q:** Can I show a message to guests about why COD is hidden? (A: Yes, use the "Message" feature in the app or theme edits).
- **Q:** What if a guest uses a valid email but doesn't log in? (A: They are still treated as a guest until they log in).

### 9. Conclusion
- Summary of benefits.
- Call to Action (CTA): Link to "Hide, Sort, Rename Payment Methods" app.

---

## Screenshot List
1. App installation page/button.
2. App Dashboard (Clean view).
3. "Create Rule" interface.
4. Selecting "Cash on Delivery" from dropdown.
5. Setting the "Customer is Guest" condition (Clear logic view).
6. The "Save" button and Active toggle (highlight location).
7. Checkout Comparison: Guest (No COD) vs Logged In (COD visible).
