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
- Cart icon number is updated - item count increases

### Actual Result

(To be filled during testing)

### Status

Not Executed

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
