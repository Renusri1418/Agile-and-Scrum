# Task 5 – Backlog Prioritisation and Estimation

## Project: Online Grocery Delivery Application

## 1. Introduction

Backlog prioritisation and estimation help the Scrum Team identify which features should be developed first and understand the relative effort required to complete each user story.

For this application, the MoSCoW prioritisation technique and Fibonacci story-point estimation are used.

---

## 2. MoSCoW Prioritisation

MoSCoW is a prioritisation technique that divides requirements into four categories:

- **Must Have:** Essential features required for the product to function.
- **Should Have:** Important features that provide significant value but are not critical for the initial release.
- **Could Have:** Useful features that can be included if time and resources permit.
- **Won't Have (for now):** Features excluded from the current release but potentially considered in the future.

### Backlog Prioritisation Table

| Story ID | User Story | Priority | Justification |
|---|---|---|---|
| US-01 | Browse Grocery Categories | Must Have | Customers need to discover products. |
| US-02 | Search for Products | Should Have | Makes product discovery faster. |
| US-03 | View Product Details | Must Have | Customers need product information before purchasing. |
| US-04 | Filter and Sort Products | Could Have | Improves browsing convenience. |
| US-05 | Add Products to Cart | Must Have | Essential for creating an order. |
| US-06 | Update Cart Quantity | Must Have | Customers must be able to adjust quantities. |
| US-07 | Remove Products from Cart | Should Have | Allows customers to correct their carts. |
| US-08 | Make Secure Payments | Must Have | Required to complete online purchases. |
| US-09 | Place a Grocery Order | Must Have | Essential for submitting purchases. |
| US-10 | Select a Delivery Slot | Should Have | Allows customers to choose a convenient delivery time. |
| US-11 | Track Order Status | Should Have | Helps customers monitor their orders. |
| US-12 | Receive Order Notifications | Could Have | Improves communication and customer experience. |

**Won't Have (for now):** Advanced personalised product recommendations are excluded from the initial release because they are not required for the basic grocery ordering workflow.

---

## 3. Fibonacci Story-Point Estimation

Story points represent the relative effort, complexity, and uncertainty involved in completing a user story.

The Fibonacci sequence is used because larger tasks have greater uncertainty in their estimates.

### Fibonacci Scale

| Story Points | Relative Complexity |
|---:|---|
| 1 | Very small |
| 2 | Small |
| 3 | Moderate |
| 5 | Medium |
| 8 | Large |
| 13 | Very large and potentially needs splitting |

Story points are relative estimates, not direct measurements of development hours.

---

## 4. Planning Poker Estimation

Planning Poker is a collaborative estimation technique used by Scrum Teams.

### Steps Involved

1. The Product Owner explains the user story and its expected value.
2. Developers discuss the requirements and clarify uncertainties.
3. Each Developer independently selects a Fibonacci story-point value.
4. All estimates are revealed simultaneously.
5. If estimates differ, team members explain their reasoning.
6. The team discusses the differences and agrees on a final estimate.

### Reference Story Selection

**Reference Story: US-01 – Browse Grocery Categories**

Estimated Size: **3 Story Points**

This story is selected as the reference because it has a clearly defined scope, moderate implementation complexity, and a straightforward expected outcome.

Other stories are compared against this reference to determine their relative complexity.

### Planning Poker Estimation Table

The following table represents a sample Planning Poker exercise and the team's agreed estimates.

| Story ID | User Story | Initial Estimate | Final Estimate |
|---|---|---:|---:|
| US-01 | Browse Grocery Categories | 3 | 3 |
| US-02 | Search for Products | 5 | 5 |
| US-03 | View Product Details | 2 | 2 |
| US-04 | Filter and Sort Products | 5 | 5 |
| US-05 | Add Products to Cart | 3 | 3 |
| US-06 | Update Cart Quantity | 2 | 2 |
| US-07 | Remove Products from Cart | 1 | 2 |
| US-08 | Make Secure Payments | 8 | 8 |
| US-09 | Place a Grocery Order | 5 | 5 |
| US-10 | Select a Delivery Slot | 5 | 5 |
| US-11 | Track Order Status | 5 | 5 |
| US-12 | Receive Order Notifications | 3 | 3 |

### Outlier Discussion

During the sample Planning Poker exercise, US-07 received different estimates from team members.

Some Developers estimated 1 point because removing a product appears simple. Others estimated 2 points because the application must also update the cart total and handle an empty cart.

After discussion, the team agreed on **2 story points**.

---

## 5. Final Prioritised Product Backlog

| Story ID | Priority | Story Points |
|---|---|---:|
| US-01 | Must Have | 3 |
| US-02 | Should Have | 5 |
| US-03 | Must Have | 2 |
| US-04 | Could Have | 5 |
| US-05 | Must Have | 3 |
| US-06 | Must Have | 2 |
| US-07 | Should Have | 2 |
| US-08 | Must Have | 8 |
| US-09 | Must Have | 5 |
| US-10 | Should Have | 5 |
| US-11 | Should Have | 5 |
| US-12 | Could Have | 3 |
| **Total** | | **48** |

### Priority Distribution

| Priority | Number of Stories |
|---|---:|
| Must Have | 6 |
| Should Have | 4 |
| Could Have | 2 |
| Won't Have (for now) | 1 excluded future feature |

---

## 6. Conclusion

MoSCoW prioritisation helps the team focus on essential functionality before developing additional features.

Planning Poker provides a collaborative method for estimating the relative complexity of user stories using Fibonacci values.

The reference story, US-01, is estimated at 3 story points. The total estimated size of the 12-story backlog is 48 story points.

These estimates and priorities provide a foundation for Sprint Planning and the selection of stories for an initial Sprint.