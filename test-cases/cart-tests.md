# Cart behaviour test cases

---

## Cart page

---

## Test Case: Add item to the cart

**Test Case ID:** TC-CART-001  
**Feature:** Cart
**Priority:** High

### Preconditions

- User is on the product listing [page](https://sauce-demo.myshopify.com/collections/all)

### Test Steps

1. Click on any available in-stock item
2. Select item options if necessary
3. Click on the [Add to Cart] button

### Expected Result

- Item is added to the cart
- Animation for the added item is displayed
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

1. Click on the [Check Out] link from the page header

### Expected Result

- User is redirected to the cart page
- All items added to the cart are listed
- Each item displays:
  - Product name
  - Product image
  - Product description
  - Price
  - Quantity
  - Total price calculated based on quantity
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

1. Click on the [Check Out] link from the page header

### Expected Result

- User is redirected to the cart page
- Message "It appears that your cart is currently empty! Continue Shopping." is displayed
- Text "Continue shopping." is displayed as a link to the "Products" page

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

1. Click on the [x] link next to any item in the cart

### Expected Result

- Item is removed from the cart
- Cart view is updated according to the new number of items
- Total order price is updated
- Header cart icon number is updated

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

1. Click on the quantity (Qty) input field for any item in the cart
2. Enter new different positive number into the input field
3. Click on the [Update] button

### Expected Result

- Item quantity number is modified
- Item total and order total prices are updated according to the new item quantity
- Header cart icon number is updated according to the new number of items

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

1. Click on the quantity (Qty) input field for any item in the cart
2. Enter 0 (zero) into the input field
3. Click on the [Update] button

### Expected Result

- Item is removed from cart
- Cart view is updated according to the new number of items
- Total order price is updated
- Header cart icon number is updated

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

1. Click on the quantity (Qty) input field for any item in the cart
2. Enter negative number into the input field
3. Click on the [Update] button

### Expected Result

- Input is ignored by the system
- Item quantity remains unchanged

### Actual Result

(To be filled during testing)

### Status

Not Executed

---

## Test Case: Change item quantity - press enter to submit

**Test Case ID:** TC-CART-008
**Feature:** Cart
**Priority:** Low

### Preconditions

- User is on the cart page
- User has at least 1 item in the cart

### Test Steps

1. Click on the quantity (Qty) input field for any item in the cart
2. Enter any other positive number into the input field
3. Press on [Enter](on Windows) or [Return](on MacOS) keyboard key

### Expected Result

- Item quantity number is modified
- Item total and order total prices are updated according to the new item quantity
- Header cart icon number is updated according to the new number of items

### Actual Result

(To be filled during testing)

### Status

Not Executed

---

## Test Case: Click on the [Continue Shopping] link

**Test Case ID:** TC-CART-09
**Feature:** Cart
**Priority:** Low

### Preconditions

- User is on the cart page

### Test Steps

1. Click on the [Continue Shopping] link

### Expected Result

- User is redirected to the default products listing page

### Actual Result

(To be filled during testing)

### Status

Not Executed

---

## Test Case: Navigate to Checkout and verify details

**Test Case ID:** TC-CART-010
**Feature:** Cart
**Priority:** High

### Preconditions

- User is on the cart page
- User has at least 1 item in the cart

### Test Steps

1. Click on the [Check Out] button

### Expected Result

- User is redirected to the Checkout page
- All items from the cart are displayed
- Correct items' quantity numbers are displayed
- Subtotal price is calculated correctly

### Actual Result

(To be filled during testing)

### Status

Not Executed

---

## Minicart component

---

## Test Case: View minicart and verify item details

**Test Case ID:** TC-MINICART-001
**Feature:** Cart
**Priority:** High

### Preconditions

- User is on any page with access to the minicart component
- User has at least 1 item in the cart

### Test Steps

1. Click on the [My Cart] link from the page header

### Expected Result

- Minicart component is displayed
- All items added to the cart are listed
- Each item displays:
  - Product name
  - Product image
  - Product description
  - Price
  - Quantitiy
  - Subtotal price calculated from item quantity
- Product name is displayed as clickable link
- Clicking the product name redirects to the product description page

### Actual Result

(To be filled during testing)

### Status

Not Executed

---

## Test Case: View empty minicart

**Test Case ID:** TC-MINICART-002
**Feature:** Cart
**Priority:** Medium

### Preconditions

- User is on any page with access to the minicart component
- User has no items in the cart

### Test Steps

1. Click on the [My Cart] link from the page header

### Expected Result

- Minicart component is displayed
- Message "Your cart is empty." is displayed

### Actual Result

(To be filled during testing)

### Status

Not Executed

---

## Test Case: Remove item from the minicart

**Test Case ID:** TC-MINICART-003
**Feature:** Cart
**Priority:** Medium

### Preconditions

- User is on any page with access to the minicart component
- User has at least 1 item in the cart

### Test Steps

1. Click on the [My Cart] link from the page header
2. Click on the [Remove] link from any item in cart

### Expected Result

- Item is removed from the cart
- Cart view is updated according to the new number of items
- Header cart icon number is updated - item count decreases

### Actual Result

(To be filled during testing)

### Status

Not Executed

---

## Test Case: Change item quantity from the minicart

**Test Case ID:** TC-MINICART-004
**Feature:** Cart
**Priority:** Low

### Preconditions

- User is on any page with access to the minicart component
- User has at least 1 item in the cart

### Test Steps

1. Click on the [My Cart] link from the page header
2. Click on the quantity input field for any item in cart
3. Enter any other positive number into the input field
4. Press [Enter](for Windows) or [Return](for MacOS) keyboard key

### Expected Result

- User is redirected to the cart page
- All items from the cart are listed
- Modified item is displayed with a new quantity number
- Item total and order total prices are displayed according to the new item quantity
- Header cart icon number is updated according to the new number of items

### Actual Result

(To be filled during testing)

### Status

Not Executed

---

## Test Case: Navigate to the cart page from the minicart component

**Test Case ID:** TC-MINICART-005
**Feature:** Cart
**Priority:** Medium

### Preconditions

- User is on any page with access to the minicart component
- User has at least 1 item in the cart

### Test Steps

1. Click on the [My Cart] link from the page header
2. Click on the [Check Out] button

### Expected Result

- User is redirected to the cart page
- All items from the cart are listed

### Actual Result

(To be filled during testing)

### Status

Not Executed

---
