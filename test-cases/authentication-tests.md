# User authentication test cases

---

## Test Case: Login with valid credentials

**Test Case ID:** TC-LOGIN-001  
**Feature:** Authentication  
**Priority:** High

### Preconditions

- Registered user account exists in the system
- User is on the [login page](https://sauce-demo.myshopify.com/account/login)

### Test Steps

1. Enter valid registered email into the email input field
2. Enter valid password for the registered account into the password input field. Click the [Sign In] button

### Expected Result

- User is successfully authenticated
- User is redirected to the "Account Details and Order History" page
- User's name is displayed under the "Your Account" header
- Login session is created

### Actual Result

(To be filled during testing)

### Status

Not Executed

---

## Test Case: Login attempt with invalid password

**Test Case ID:** TC-LOGIN-002  
**Feature:** Authentication  
**Priority:** High

### Preconditions

- Registered user account exists in the system
- User is on the [login page](https://sauce-demo.myshopify.com/account/login)

### Test Steps

1. Enter valid registered email into the email input field
2. Enter invalid password into the password input field
3. Click the [Sign In] button

### Expected Result

- User is not authenticated
- User remains on the login page
- Error message "Incorrect email or password." is displayed
- No session is created

### Actual Result

(To be filled during testing)

### Status

Not Executed

---

## Test Case: Login attempt with invalid email

**Test Case ID:** TC-LOGIN-003  
**Feature:** Authentication  
**Priority:** High

### Preconditions

- Registered user account exists in the system
- User is on the [login page](https://sauce-demo.myshopify.com/account/login)

### Test Steps

1. Enter properly formatted invalid email into the email input field (e.g. test@mail.com)
2. Enter valid password into the password input field
3. Click the [Sign In] button

### Expected Result

- User is not authenticated
- User remains on the login page
- Error message "Incorrect email or password." is displayed
- No session is created

### Actual Result

(To be filled during testing)

### Status

Not Executed

---

## Test Case: Login attempt with invalid format email

**Test Case ID:** TC-LOGIN-004  
**Feature:** Authentication  
**Priority:** Low

### Preconditions

- Registered user account exists in the system
- User is on the [login page](https://sauce-demo.myshopify.com/account/login)

### Test Steps

1. Enter invalid format email into the email input field (e.g. without '@' symbol : "testemail")
2. Enter valid password into the password input field
3. Click the [Sign In] button

### Expected Result

- User is not authenticated
- User remains on the login page
- Default browser tooltip is displayed prompting user to check the email format
- No session is created

### Actual Result

(To be filled during testing)

### Status

Not Executed

---

## Test Case: Login attempt with an empty email field

**Test Case ID:** TC-LOGIN-005  
**Feature:** Authentication  
**Priority:** Medium

### Preconditions

- Registered user account exists in the system
- User is on the [login page](https://sauce-demo.myshopify.com/account/login)

### Test Steps

1. Leave the email input field empty
2. Enter valid password into the password input field
3. Click the [Sign In] button

### Expected Result

- User is not authenticated
- User remains on the login page
- Error message "Incorrect email or password." is displayed
- No session is created

### Actual Result

(To be filled during testing)

### Status

Not Executed

---

## Test Case: Login attempt with an empty password field

**Test Case ID:** TC-LOGIN-006  
**Feature:** Authentication  
**Priority:** Medium

### Preconditions

- Registered user account exists in the system
- User is on the [login page](https://sauce-demo.myshopify.com/account/login)

### Test Steps

1. Enter valid registered email into the email input field
2. Leave the password input field empty
3. Click the [Sign In] button

### Expected Result

- User is not authenticated
- User remains on the login page
- Error message "Incorrect email or password." is displayed
- No session is created

### Actual Result

(To be filled during testing)

### Status

Not Executed

---

## Test Case: Multiple rapid login attempts with invalid credentials

**Test Case ID:** TC-LOGIN-007  
**Feature:** Authentication  
**Priority:** Medium

### Preconditions

- Registered user account exists in the system
- User is on the [login page](https://sauce-demo.myshopify.com/account/login)

### Test Steps

1. Enter valid registered email into the email input field
2. Enter invalid password into the password input field
3. Click the [Sign In] button
4. Repeat steps 1-3 multiple times (10-20 times)

### Expected Result

- User is not authenticated
- User remains on the login page
- Error message "Incorrect email or password." is displayed
- No session is created
- Captcha verification pop-up is displayed after several unsuccessful login attempts

### Actual Result

(To be filled during testing)

### Status

Not Executed

---

## Test Case: Login with leading/trailing spaces in the email field

**Test Case ID:** TC-LOGIN-008  
**Feature:** Authentication  
**Priority:** Medium

### Preconditions

- Registered user account exists in the system
- User is on the [login page](https://sauce-demo.myshopify.com/account/login)

### Test Steps

1. Enter valid registered email with several leading and trailing spaces into the email input field (e.g. " test@test.com ")
2. Enter valid password into the password input field
3. Click the [Sign In] button

### Expected Result

- User is successfully authenticated
- User is redirected to the "Account Details and Order History" page
- User's name is displayed under the "Your Account" header
- Login session is created

### Actual Result

(To be filled during testing)

### Status

Not Executed

---

## Test Case: Password field masking

**Test Case ID:** TC-LOGIN-009  
**Feature:** Authentication  
**Priority:** Low

### Preconditions

- User is on the [login page](https://sauce-demo.myshopify.com/account/login)

### Test Steps

1. Enter password into the password input field

### Expected Result

- Pasword characters are masked (e.g. \*\*\*\*\*\*)

### Actual Result

(To be filled during testing)

### Status

Not Executed

---
