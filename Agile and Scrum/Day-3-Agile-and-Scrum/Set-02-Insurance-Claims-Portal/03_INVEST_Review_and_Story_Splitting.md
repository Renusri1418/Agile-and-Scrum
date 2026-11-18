# Task 3 – INVEST Review and Story Splitting

## Project: Insurance Claims Portal

## 1. INVEST Criteria

INVEST is a set of six principles used to evaluate the quality of user stories.

| Principle | Meaning |
|---|---|
| Independent | The story should be developed with minimal dependency on other stories. |
| Negotiable | The story should allow discussion between the Product Owner and Developers. |
| Valuable | The story should provide value to the customer or business. |
| Estimable | The team should be able to estimate the effort required. |
| Small | The story should be small enough to complete within a sprint. |
| Testable | The story should have clear conditions for verifying completion. |

## 2. INVEST Evaluation of User Stories

| Story ID | Independent | Negotiable | Valuable | Estimable | Small | Testable | Result |
|---|---|---|---|---|---|---|---|
| US-01 | Yes | Yes | Yes | Yes | Yes | Yes | Pass |
| US-02 | Yes | Yes | Yes | Yes | Yes | Yes | Pass |
| US-03 | Yes | Yes | Yes | Yes | Yes | Yes | Pass |
| US-04 | Yes | Yes | Yes | Yes | No | Yes | Needs splitting |
| US-05 | Yes | Yes | Yes | Yes | Yes | Yes | Pass |
| US-06 | Yes | Yes | Yes | Yes | Yes | Yes | Pass |
| US-07 | Yes | Yes | Yes | Yes | Yes | Yes | Pass |
| US-08 | Yes | Yes | Yes | Yes | Yes | Yes | Pass |
| US-09 | Yes | Yes | Yes | Yes | Yes | Yes | Pass |
| US-10 | Yes | Yes | Yes | Yes | Yes | Yes | Pass |
| US-11 | Yes | Yes | Yes | Yes | Yes | Yes | Pass |
| US-12 | Yes | Yes | Yes | Yes | Yes | Yes | Pass |
| US-13 | Yes | Yes | Yes | Yes | Yes | Yes | Pass |
| US-14 | Yes | Yes | Yes | Yes | Yes | Yes | Pass |

## 3. Identification of an Oversized Story

**Original Story – US-04**

As a policyholder, I want to submit my claim so that the insurance company can begin processing it.

**Issue identified:**

The claim submission process may involve multiple activities, such as checking required information, submitting the claim, and receiving confirmation. Treating the entire workflow as one story may make estimation and testing difficult.

## 4. Vertical Story Splitting

The oversized story is divided into two smaller, user-focused stories.

### Revised Story – US-04: Submit a Claim

As a policyholder, I want to submit my completed claim details so that the insurance company can begin processing my claim.

**Acceptance outcome:** The system accepts a claim submission when all mandatory information is valid.

### New Story – US-15: Receive Claim Confirmation

As a policyholder, I want to receive a claim reference number after submission so that I can identify and track my claim.

**Acceptance outcome:** The system displays a unique claim reference number after successful submission.

Both stories deliver independently testable user value and represent complete vertical slices of functionality.

## 5. Why Vertical Splitting Is Preferred

Vertical splitting divides a feature into smaller pieces that each provide usable functionality to the customer.

For example, instead of splitting claim submission into technical tasks such as frontend development, database development, and API development, the team divides it into customer-visible outcomes:

- Submit completed claim details.
- Receive a claim reference number.

This approach supports incremental delivery, easier testing, better estimation, and faster feedback.

## 6. Updated Backlog Summary

| Epic | Original Stories | New Stories |
|---|---:|---:|
| Claim Registration | 4 | 5 |
| Document Upload | 4 | 4 |
| Claim Tracking | 3 | 3 |
| Settlement Notifications | 3 | 3 |
| **Total** | **14** | **15** |

## 7. Conclusion

The INVEST review identified US-04 as an oversized story. It was split into two smaller vertical stories, US-04 and US-15.

The revised backlog contains 15 user stories. These stories are more manageable, easier to estimate, and can be validated through clear customer-focused outcomes.