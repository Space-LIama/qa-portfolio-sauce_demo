# Bug reports

---

## Bug: User is able to access login page when login session is active

**BUG ID:** B-001  
**Severity:** Low  
**Priority:** Low  
**Reproductible:** Always  
**Environment:** MacOS 26.3.1 - Safari 26.3.1 / Chrome 146.0.7680.165

### Description

User is able to access login page via URL "https://sauce-demo.myshopify.com/account/login" after a successful login and during an active login session

### Preconditions

- Registered user account exists in the system

### Steps to reproduce

1. Navigate to the home page url "https://sauce-demo.myshopify.com"
2. Click on the link [Log In] from the page header
3. Enter valid registered email into the email input field
4. Enter valid password into the password input field
5. Click on the [Sign In] button
6. Navigate to the logn page url "https://sauce-demo.myshopify.com/account/login" using the browser search bar

### Expected result

- User is redirected to the "Account Details and Order History" page

### Actual result

- Login page is displayed despite active login session

### Notes

This behavior may cause confusion for users. Redirecting authenticated users away from the login page should be considered.

### Attachments

<video src="https://github.com/user-attachments/assets/40fa2fba-dcbd-4e25-bbf4-bf0c9d01f001" controls preload></video>

---

## Bug: Endless loading occurs in the minicart component when a new item is added to the cart

**BUG ID:** B-002  
**Severity:** Medium  
**Priority:** High  
**Reproductible:** Always  
**Environment:** MacOS 26.3.1 - Safari 26.3.1 / Chrome 146.0.7680.165

### Description

Endless loading with visible throbber animation occurs in the minicart component after adding a new item to the cart

### Preconditions

none

### Steps to reproduce

1. Navigate to the home page url "https://sauce-demo.myshopify.com"
2. Click on the [Catalog] menu option
3. Click on any of the in-stock items
4. Choose options if necessary and click on the [Add to Cart] button
5. Click on the [My Cart] header link

### Expected result

- Minicart component with all added to the cart items is visible

### Actual result

- Minicart component is displayed with endless strobber loading animation

### Attachments

<video src="https://github.com/user-attachments/assets/a7d863fb-64c6-40a3-ac27-8f6d90706448" controls preload></video>

---
