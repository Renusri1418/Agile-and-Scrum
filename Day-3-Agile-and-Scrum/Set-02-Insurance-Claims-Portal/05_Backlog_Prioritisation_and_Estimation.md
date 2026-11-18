# Task 5 – Backlog Prioritisation and Estimation

## Project: Insurance Claims Portal

## 1. Planning Poker

Planning Poker is an estimation technique used by Scrum Teams to estimate the relative effort, complexity, and uncertainty involved in completing user stories.

Each team member selects a Fibonacci-based estimate. The team discusses differences in estimates and agrees on a final story point value.

### Fibonacci Estimation Scale

| Story Points | Meaning |
|---:|---|
| 1 | Very simple task |
| 2 | Small task with limited complexity |
| 3 | Moderate task |
| 5 | Medium complexity |
| 8 | High complexity or uncertainty |
| 13 | Very large or complex story that may need splitting |

## 2. Prioritisation Criteria

The stories are prioritised based on:

- Business value to the insurance company.
- Importance to policyholders.
- Dependencies between features.
- Risk and implementation complexity.

### Priority Levels

- **High:** Essential functionality required for the core claims process.
- **Medium:** Important functionality that improves the user experience and operational workflow.
- **Low:** Useful functionality that can be delivered after essential features.

## 3. Estimated Product Backlog

The following estimates are representative Planning Poker results for the Scrum Team exercise.

| Story ID | User Story | Priority | Story Points |
|---|---|---|---:|
| US-01 | Secure Login | High | 3 |
| US-02 | Select Insurance Policy | High | 2 |
| US-03 | Enter Incident Details | High | 5 |
| US-04 | Submit a Claim | High | 5 |
| US-15 | Receive Claim Confirmation | High | 2 |
| US-05 | Upload Identity Documents | High | 3 |
| US-06 | Upload Incident Photographs | Medium | 3 |
| US-07 | Upload Bills and Receipts | High | 3 |
| US-08 | View Uploaded Documents | Medium | 2 |
| US-09 | View Submitted Claims | Medium | 3 |
| US-10 | View Current Claim Status | High | 2 |
| US-11 | View Requests for Additional Information | Medium | 3 |
| US-12 | Receive Claim Status Notifications | Medium | 3 |
| US-13 | Receive Approval or Rejection Notifications | High | 2 |
| US-14 | View Settlement Details | Medium | 5 |
| | **Total** | | **46** |

## 4. Planning Poker Outlier Discussion

### Example: US-03 – Enter Incident Details

During the estimation exercise, team members provided different estimates:

| Team Member | Initial Estimate |
|---|---:|
| Developer 1 | 3 |
| Developer 2 | 5 |
| Developer 3 | 8 |
| Developer 4 | 5 |
| Developer 5 | 3 |

### Reason for Difference

Some team members considered incident details entry a simple form-development task. Others considered the additional validation rules, incident categories, and required field checks.

### Discussion and Final Decision

After discussing the complexity and validation requirements, the team agreed on **5 story points**.

The final estimate represents the relative effort and uncertainty involved in implementing and testing the feature.

## 5. Backlog Point Calculation

| Epic | Story Points |
|---|---:|
| Claim Registration (US-01 to US-04 and US-15) | 17 |
| Document Upload (US-05 to US-08) | 11 |
| Claim Tracking (US-09 to US-11) | 8 |
| Settlement Notifications (US-12 to US-14) | 10 |
| **Total Backlog Estimate** | **46** |

## 6. Story Points vs Hours

| Story Points | Hours |
|---|---|
| Measure relative complexity, effort, and uncertainty | Measure actual time spent |
| Estimated collaboratively by the Scrum Team | Recorded based on working time |
| Not directly convertible into hours | Expressed in hours |
| Used for backlog estimation and sprint planning | Used for task-level tracking and capacity planning |

For example, a story estimated at 5 points does not necessarily require five hours. It represents a relative level of effort compared with other stories.

## 7. Conclusion

The Insurance Claims Portal backlog contains 15 user stories with a total estimated size of 46 story points.

Planning Poker supports collaborative estimation and encourages discussion among Developers. Prioritisation ensures that essential features such as claim registration, document submission, and claim tracking receive appropriate attention.