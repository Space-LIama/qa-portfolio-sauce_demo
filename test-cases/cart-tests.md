# Cart behaviour test cases

---

## Test Case: Add item to the cart

**Test Case ID:** TC-CART-001  
**Feature:** Cart
**Priority:** High

### Preconditions

- User is on product listing [page](https://sauce-demo.myshopify.com/collections/all)

### Test Steps

1. Click on any available in-stock item
2. Select item options if necessary
3. Click on [Add to Cart] button

### Expected Result

- Item is added to cart
- Animation for the added item is dispaled
- Header cart icon number is updated - item count increases

### Actual Result

(To be filled during testing)

### Status

Not Executed

---

## Test Case: Navigate to cart and verify item details

**Test Case ID:** TC-CART-002
**Feature:** Cart
**Priority:** High

### Preconditions

- User is on any page with access to the cart
- User has at least 1 item in the cart

### Test Steps

1. Click on [Check Out] link from the page header

### Expected Result

- User is redirected to the cart page
- All items added to the cart are listed
- Each item displays:
  - Product name
  - Product image
  - Product description
  - Price
  - Quantitiy
  - Total price considering quantity
- Product name is displayed as a link to the product description page

### Actual Result

(To be filled during testing)

### Status

Not Executed

---

## Test Case: View empty cart

**Test Case ID:** TC-CART-003
**Feature:** Cart
**Priority:** Medium

### Preconditions

- User is on any page with access to the cart
- User has no items in the cart

### Test Steps

1. Click on [Check Out] link from the page header

### Expected Result

- User is redirected to the cart page
- Message "It appears that your cart is currently empty! Continue Shopping." is displayed
- Text "Continue shoping." is displayed as a link to the "Products" page

### Actual Result

(To be filled during testing)

### Status

Not Executed

---

## Test Case: Remove item from the cart

**Test Case ID:** TC-CART-004
**Feature:** Cart
**Priority:** High

### Preconditions

- User is on the cart page
- User has at least 1 item in the cart

### Test Steps

1. Click on [x] link next to any item in cart

### Expected Result

- Item is removed from cart
- Cart view is updated according to the new number of items
- Total order price is updated according to the new number of items
- Header cart icon number is updated according to the new number of items in cart

### Actual Result

(To be filled during testing)

### Status

Not Executed

---

## Test Case: Change item quantity - positive

**Test Case ID:** TC-CART-005
**Feature:** Cart
**Priority:** High

### Preconditions

- User is on the cart page
- User has at least 1 item in the cart

### Test Steps

1. Click on the quantity (Qty) input field for any item in cart
2. Enter new different positive quantity number into the input field
3. Click on [Update] button

### Expected Result

- Item quantity number is modified
- Item total and order total prices are updated according to the new quantities
- Header cart icon number is updated according to the new number of items in cart

### Actual Result

(To be filled during testing)

### Status

Not Executed

---

## Test Case: Change item quantity - 0 (zero)

**Test Case ID:** TC-CART-006
**Feature:** Cart
**Priority:** Medium

### Preconditions

- User is on the cart page
- User has at least 1 item in the cart

### Test Steps

1. Click on the quantity (Qty) input field for any item in cart
2. Enter 0 (zero) into the input field
3. Click on [Update] button

### Expected Result

- Item is removed from cart
- Cart view is updated according to the new number of items
- Total order price is updated according to the new number of items
- Header cart icon number is updated according to the new number of items in cart

### Actual Result

(To be filled during testing)

### Status

Not Executed

---

## Test Case: Change item quantity - negative

**Test Case ID:** TC-CART-007
**Feature:** Cart
**Priority:** High

### Preconditions

- User is on the cart page
- User has at least 1 item in the cart

### Test Steps

1. Click on the quantity (Qty) input field for any item in cart
2. Enter any negative number into the input field
3. Click on [Update] button

### Expected Result

- Input is ignored by the system
- Item quantity remains unchanged

### Actual Result

(To be filled during testing)

### Status

Not Executed

---

MINI CART

---

## Test Case: View cart and verify item details

**Test Case ID:** TC-CART-002
**Feature:** Cart
**Priority:** High

### Preconditions

- User is on any page with access to the cart
- User has at least 1 item in the cart

### Test Steps

1. Click on [My Cart] link from the page header

### Expected Result

- Cart component is displayed
- All items added to the cart are listed
- Each item displays:
  - Product name
  - Product image
  - Product description
  - Price
  - Quantitiy
- Product name is displayed as clickable link
- Clicking the product name redirects to the product description page

### Actual Result

(To be filled during testing)

### Status

Not Executed

---

## Test Case: View empty cart

**Test Case ID:** TC-CART-003
**Feature:** Cart
**Priority:** Medium

### Preconditions

- User is on any page with access to the cart
- User has no items in the cart

### Test Steps

1. Click on [My Cart] link from the page header

### Expected Result

- Cart component is displayed
- Message "Your cart is empty." is displayed

### Actual Result

(To be filled during testing)

### Status

Not Executed

---

## Test Case: Remove item from the cart

**Test Case ID:** TC-CART-004
**Feature:** Cart
**Priority:** High

### Preconditions

- User is on any page with access to the cart
- User has at least 1 item in the cart

### Test Steps

1. Click on [My Cart] link from the page header
2. Click on [Remove] link from any item in cart

### Expected Result

- Item is removed from the cart
- Cart view is updated according to the new number of items
- Cart icon number is updated - item count decreases

### Actual Result

(To be filled during testing)

### Status

Not Executed

---

## Test Case: Change item quantity - positive

**Test Case ID:** TC-CART-005
**Feature:** Cart
**Priority:** High

### Preconditions

- User is on any page with access to the cart
- User has at least 1 item in the cart

### Test Steps

1. Click on [My Cart] link from the page header
2. Click on the quantity input field from any item in cart
3. Change the quantity to any different positive number
4. Press [Enter]\(for Windows) or [Return]\(for MacOS) keyboard key

### Expected Result

- Cart component is displayed
- All items added to the cart are listed
- Each item displays:
  - Product name
  - Product image
  - Product description
  - Price
  - Quantitiy
- Product name is displayed as clickable link
- Clicking the product name redirects to the product description page

### Actual Result

(To be filled during testing)

### Status

Not Executed

---
