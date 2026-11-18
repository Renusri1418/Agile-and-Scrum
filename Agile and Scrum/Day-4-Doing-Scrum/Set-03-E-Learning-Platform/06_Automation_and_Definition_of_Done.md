# Task 6 – Automation and Definition of Done

## 1. Introduction

The Definition of Done (DoD) describes the quality conditions that must be satisfied before a user story is considered complete.

Automation helps the development team verify these conditions consistently and efficiently.

## 2. Role of Automation

### A. Unit Testing

- Unit tests check individual functions and components.
- They identify errors early in development.
- Automated tests can run whenever code changes are submitted.
- They help ensure that existing functionality continues to work.

### B. Linting

- Linting checks source code for common errors and style issues.
- It helps maintain consistent coding standards.
- It identifies possible problems before code review.
- It improves code readability and maintainability.

### C. Automated Build Pipeline

- Automatically builds the application.
- Runs unit and integration tests.
- Checks code quality.
- Provides feedback when a build or test fails.
- Helps prevent defective code from being merged.

## 3. Definition of Done Checklist

A user story is considered Done when:

- [ ] Development work is completed.
- [ ] Code follows agreed coding standards.
- [ ] Unit tests pass successfully.
- [ ] Required integration tests pass.
- [ ] Code review is completed.
- [ ] Acceptance criteria are satisfied.
- [ ] No critical defects remain.
- [ ] Relevant documentation is updated.

## 4. Mapping Automation to the Build Pipeline

| Pipeline Stage | Automated Activity | DoD Support |
|---|---|---|
| Build | Compile the application | Confirms that the application builds successfully |
| Test | Run automated unit and integration tests | Confirms expected functionality |
| Review | Run linting and static code analysis; perform code review | Checks code quality and standards |
| Merge | Merge approved changes after required checks pass | Ensures only approved changes enter the main branch |

## 5. Benefits of Automation

- Reduces repetitive manual work.
- Detects defects early.
- Improves code quality.
- Makes testing more consistent.
- Provides faster feedback to developers.
- Helps maintain the Definition of Done.

## 6. Conclusion

Automation supports the Definition of Done by checking code quality, building the application and executing tests. Unit testing, linting and automated pipelines help the team deliver reliable software while reducing manual effort.