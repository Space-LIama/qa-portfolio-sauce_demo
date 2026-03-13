## Test Case: Login with valid credentials

**Test Case ID:** TC-LOGIN-001  
**Feature:** Authentication  
**Priority:** High

### Preconditions

- User account excists
- User is on the [login page](https://sauce-demo.myshopify.com/account/login)

### Test Steps

1. Enter valid email into the email input field
2. Enter valid password into the password input field
3. Click the [Sign In] button

### Expected Result

User is redirected to the "Account Details and Order History" page

### Actual Result

(To be filled durnig testing)

### Status

Not Executed

---

## Test Case: Login attempt with invalid password

**Test Case ID:** TC-LOGIN-002
**Feature:** Authentication  
**Priority:** High

### Preconditions

- User account excists
- User is on the [login page](https://sauce-demo.myshopify.com/account/login)

### Test Steps

1. Enter valid email into the email input field
2. Enter invalid password into the password input field
3. Click the [Sign In] button

### Expected Result

User is not logged in. Error message "Incorrect email or password." is displayed to the user

### Actual Result

(To be filled durnig testing)

### Status

Not Executed

---

## Test Case: Login attempt with invalid email

**Test Case ID:** TC-LOGIN-003
**Feature:** Authentication  
**Priority:** High

### Preconditions

- User account excists
- User is on the [login page](https://sauce-demo.myshopify.com/account/login)

### Test Steps

1. Enter properly formated invalid email into the email input field (e.g. test@mail.com)
2. Enter valid password into the password input field
3. Click the [Sign In] button

### Expected Result

User is not logged in. Error message "Incorrect email or password." is displayed to the user

### Actual Result

(To be filled durnig testing)

### Status

Not Executed

---

## Test Case: Login attempt with invalid format email

**Test Case ID:** TC-LOGIN-004
**Feature:** Authentication  
**Priority:** Low

### Preconditions

- User account excists
- User is on the [login page](https://sauce-demo.myshopify.com/account/login)

### Test Steps

1. Enter invalid format email into the email input field (e.g. without '@' symbol : "testemail")
2. Enter valid password into the password input field
3. Click the [Sign In] button

### Expected Result

User is not logged in. Default browser tooltip is displayed to the user prompting to check the email format

### Actual Result

(To be filled durnig testing)

### Status

Not Executed

---
