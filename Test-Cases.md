
# E-Commerce Website - Test Cases

## Module 1: Login


### TC_LOGIN_001
**Test Scenario:** Login with valid credentials

**Precondition:** A registered test account exists.

**Steps:**
1. Open the login page.
2. Enter username: standard_user
3. Enter password: secret_sauce
4. Click the Login button.

**Expected Result:** The user should log in successfully and navigate to the Products page.

**Actual Result:** The user logged in successfully and the Products page opened.

**Status:** PASS


---

### TC_LOGIN_002
**Test Scenario:** Login with an incorrect password

**Steps:**
1. Open the login page.
2. Enter a registered email address.
3. Enter an incorrect password.
4. Click the Login button.

**Expected Result:** The user should see an appropriate error message.

**Actual Result:** Not Executed

**Status:** Not Executed

---

### TC_LOGIN_003
**Test Scenario:** Login with empty fields

**Steps:**
1. Open the login page.
2. Leave the email and password fields empty.
3. Click the Login button.

**Expected Result:** The system should show validation messages or prevent submission.

**Actual Result:** Not Executed

**Status:** Not Executed

---

## Module 2: Product Search

### TC_SEARCH_001
**Test Scenario:** Search for an existing product

**Steps:**
1. Open the product search page.
2. Enter a product name.
3. Click Search.

**Expected Result:** Relevant matching products should be displayed.

**Actual Result:** Not Executed

**Status:** Not Executed

---

### TC_SEARCH_002
**Test Scenario:** Search for a product that does not exist

**Steps:**
1. Enter a product name that is not available.
2. Click Search.

**Expected Result:** An appropriate no-results message should be displayed.

**Actual Result:** Not Executed

**Status:** Not Executed

---

## Module 3: Shopping Cart

### TC_CART_001
**Test Scenario:** Add a product to the cart

**Steps:**
1. Open a product details page.
2. Click Add to Cart.
3. Open the shopping cart.

**Expected Result:** The selected product should appear in the cart.

**Actual Result:** Not Executed

**Status:** Not Executed

---

### TC_CART_002
**Test Scenario:** Remove a product from the cart

**Steps:**
1. Add a product to the cart.
2. Open the shopping cart.
3. Click Remove.

**Expected Result:** The selected product should be removed from the cart.

**Actual Result:** Not Executed

**Status:** Not Executed

---

## Testing Note

These are planned test cases. Execute them on a test website and record the actual results before marking them Pass or Fail.
