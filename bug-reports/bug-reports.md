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

1. Navigate to the login page "https://sauce-demo.myshopify.com/account/login"
2. Enter valid registered email into the email input field
3. Enter valid password into the password input field
4. Click the [Sign In] button
5. Navigate to the login page from the step 1 "https://sauce-demo.myshopify.com/account/login"

### Expected result

- User is redirected to the "Account Details and Order History" page

### Actual result

- Login page is displayed despite active login session

### Notes

This behavior may cause confusion for users. Redirecting authenticated users away from the login page should be considered.

### Attachments

<video src="https://github.com/user-attachments/assets/40fa2fba-dcbd-4e25-bbf4-bf0c9d01f001" controls preload></video>




