# Task 4 – Acceptance Criteria

## Project: Online Grocery Delivery Application

## 1. Introduction

Acceptance criteria define the conditions that a user story must satisfy before it can be considered complete.

In this assignment, acceptance criteria are written using the Given / When / Then format:

- **Given:** Describes the initial condition or context.
- **When:** Describes the action performed by the user.
- **Then:** Describes the expected result.

Acceptance criteria are prepared for five user stories from the product backlog. Both positive and negative scenarios are included.

---

## 2. US-01 – Browse Grocery Categories

**User Story:**

As a customer, I want to browse groceries by categories such as fruits, vegetables, dairy, and beverages, so that I can easily find the products I need.

### Acceptance Criteria

**Scenario 1: Successfully display grocery categories**

- Given the customer has opened the grocery application.
- When the customer navigates to the categories section.
- Then the application should display available categories such as fruits, vegetables, dairy, and beverages.

**Scenario 2: Open a selected category**

- Given the grocery categories are displayed.
- When the customer selects the fruits category.
- Then the application should display the products available under fruits.

---

## 3. US-02 – Search for Products

**User Story:**

As a customer, I want to search for grocery products using product names, so that I can quickly locate specific items without browsing every category.

### Acceptance Criteria

**Scenario 1: Search for an existing product**

- Given the customer is on the product search screen.
- When the customer enters "Milk" in the search field.
- Then the application should display matching milk products.

**Scenario 2: Search for a product that does not exist (Negative Scenario)**

- Given the customer is on the product search screen.
- When the customer searches for a product that is not available in the catalogue.
- Then the application should display a message stating "No products found" and allow the customer to modify the search.

---

## 4. US-05 – Add Products to Cart

**User Story:**

As a customer, I want to add grocery products to my shopping cart, so that I can collect all the items I intend to purchase.

### Acceptance Criteria

**Scenario 1: Successfully add a product to the cart**

- Given the customer is viewing an available grocery product.
- When the customer clicks the Add to Cart button.
- Then the selected product should be added to the shopping cart with its correct name, price, and default quantity.

**Scenario 2: Verify cart quantity**

- Given the customer has added a product to the cart.
- When the customer opens the shopping cart.
- Then the application should display the selected product and its quantity correctly.

---

## 5. US-08 – Make Secure Payments

**User Story:**

As a customer, I want to complete my grocery payment using a supported UPI payment method, so that I can securely pay for my order.

### Acceptance Criteria

**Scenario 1: Successful UPI payment**

- Given the customer has reviewed the order and selected UPI as the payment method.
- When the customer completes the payment successfully.
- Then the application should display a payment confirmation and update the order payment status to Paid.

**Scenario 2: Failed UPI payment**

- Given the customer has selected UPI as the payment method.
- When the payment transaction fails.
- Then the application should display a payment failure message and allow the customer to retry the payment.

---

## 6. US-09 – Place a Grocery Order

**User Story:**

As a customer, I want to submit my reviewed shopping cart with a valid delivery address, so that the application can create a confirmed grocery order.

### Acceptance Criteria

**Scenario 1: Successfully submit an order**

- Given the customer has reviewed the shopping cart and entered a valid delivery address.
- When the customer submits the order.
- Then the application should create the order and display a unique order confirmation number.

**Scenario 2: Submit an order without a valid delivery address**

- Given the customer has items in the shopping cart but has not entered a valid delivery address.
- When the customer attempts to submit the order.
- Then the application should prevent order creation and display a message requesting a valid delivery address.

---

## 7. Acceptance Criteria Summary

| User Story ID | User Story | Scenarios |
|---|---|---:|
| US-01 | Browse Grocery Categories | 2 |
| US-02 | Search for Products | 2 |
| US-05 | Add Products to Cart | 2 |
| US-08 | Make Secure Payments | 2 |
| US-09 | Place a Grocery Order | 2 |
| **Total** | **5 User Stories** | **10** |

### Negative Scenarios Covered

1. Searching for a product that does not exist.
2. Failed UPI payment.
3. Submitting an order without a valid delivery address.

## 8. Conclusion

Acceptance criteria provide a clear understanding of the expected behaviour of each user story.

Using the Given / When / Then format helps the Product Owner, Developers, and testers agree on the expected results before implementation.

The five selected user stories include positive and negative scenarios to ensure that both successful operations and error conditions are considered during testing.