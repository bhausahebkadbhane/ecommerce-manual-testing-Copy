
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
2. Enter username: `standard_user`
3. Enter an incorrect password: `wrong_password`
4. Click the Login button.

**Expected Result:** The user should see an appropriate error message and should not be logged in.

**Actual Result:** The login failed, and the website displayed the following error message: "Epic sadface: Username and password do not match any user in this service."

**Status:** PASS

---

### TC_LOGIN_003
**Test Scenario:** Login with empty fields

**Steps:**
1. Open the login page.
2. Leave the username and password fields empty.
3. Click the Login button.

**Expected Result:** The system should display a validation message and prevent login.

**Actual Result:** Login was unsuccessful. The website displayed the error message: "Epic sadface: Username is required."

**Status:** PASS

---

### TC_SEARCH_001
**Test Scenario:** Search for an existing product

**Test Website:** Automation Exercise (https://automationexercise.com/)

**Steps:**
1. Open the Automation Exercise website.
2. Navigate to the Products section.
3. Enter `Blue Top` in the product search box.
4. Click the Search button.

**Expected Result:** Relevant matching products should be displayed.

**Actual Result:** The `Blue Top` product appeared in the search results.

**Status:** PASS

---

### TC_SEARCH_002
**Test Scenario:** Search for a product that does not exist

**Test Website:** Automation Exercise (https://automationexercise.com/)

**Steps:**
1. Open the Automation Exercise website.
2. Navigate to the Products section.
3. Enter `XYZ123NonExistingProduct` in the product search box.
4. Click the Search button.

**Expected Result:** No matching products should be displayed for the search term.

**Actual Result:** No products were displayed after searching for `XYZ123NonExistingProduct`.

**Status:** PASS

---

## Module 3: Shopping Cart

### TC_CART_001
**Test Scenario:** Add a product to the cart

**Steps:**
1. Log in to SauceDemo using valid credentials.
2. Open the Products page.
3. Click Add to cart for a product.
4. Open the shopping cart.

**Expected Result:** The selected product should appear in the shopping cart.

**Actual Result:** The product was successfully added to the cart and appeared in the shopping cart.

**Status:** PASS

---

### TC_CART_002
**Test Scenario:** Remove a product from the cart

**Steps:**
1. Log in to SauceDemo using valid credentials.
2. Add a product to the cart.
3. Open the shopping cart.
4. Click the Remove button for the selected product.

**Expected Result:** The selected product should be removed from the shopping cart.

**Actual Result:** The product was successfully removed from the cart after clicking the Remove button.

**Status:** PASS

---

## Testing Note

The seven test cases documented above were executed manually on SauceDemo and Automation Exercise.

The recorded results reflect the behavior observed during testing. Other features listed in the Test Plan, including registration, logout, checkout, and order confirmation, have not yet been tested as part of this project.
