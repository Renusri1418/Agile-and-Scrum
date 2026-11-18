# Task 6 – Sprint Retrospective and Definition of Done Pipeline

## 1. Introduction

A Sprint Retrospective is a Scrum event in which the team reflects on its performance and identifies improvements for the next sprint.

The Start-Stop-Continue method is used to organise feedback.

## 2. Start-Stop-Continue Retrospective

### Start

- Start confirming external dependencies before development begins.
- Start sharing API contracts early with all developers.
- Start reviewing sprint progress regularly.

### Stop

- Stop waiting until the last moment to report blockers.
- Stop accepting additional work without discussing its impact.
- Stop delaying testing until the end of the sprint.

### Continue

- Continue conducting daily stand-up meetings.
- Continue collaborating across development and testing.
- Continue prioritising work based on business value.

## 3. Three SMART Action Items

SMART means Specific, Measurable, Achievable, Relevant and Time-bound.

| Action Item | Owner | Success Measure | Deadline |
|---|---|---|---|
| Confirm external API dependencies before sprint development begins | Scrum Master | All required API dependencies are identified and tracked | Before the next sprint |
| Share API contracts with developers before implementation | Backend Developer | All selected stories have documented API contracts | Before the next sprint starts |
| Perform testing continuously during development | QA Engineer | Every completed story has documented test results before review | Throughout the next sprint |

## 4. Definition of Done (DoD)

Definition of Done describes the quality conditions that must be satisfied before a user story is considered complete.

The team's DoD includes:

- Code implementation is completed.
- Code follows agreed coding standards.
- Unit tests are executed successfully.
- Integration tests are completed where required.
- Code review is completed.
- Acceptance criteria are satisfied.
- No critical defects remain.
- Relevant documentation is updated.

## 5. Mapping Definition of Done to the Build Pipeline

A build pipeline automates activities that help verify the quality of software before it is merged.

| Pipeline Stage | Activity | Related DoD Condition |
|---|---|---|
| Build | Compile the application and check dependencies | Application builds successfully |
| Test | Run unit and integration tests | Tests pass successfully |
| Review | Perform code review and static analysis | Code follows standards and review is approved |
| Merge | Merge approved changes into the main branch | Changes are integrated successfully |

### Explanation

**Build:** The pipeline compiles the application and checks whether the code can be built successfully.

**Test:** Automated unit and integration tests check whether the application behaves as expected.

**Review:** Developers review code changes and automated linting or static analysis tools identify possible code-quality issues.

**Merge:** Once the required checks and reviews pass, the changes can be merged into the main branch.

Automation makes the process faster, more consistent and less dependent on manual checks. It helps the team maintain the Definition of Done.

## 6. Conclusion

The retrospective identifies improvements in dependency management, communication and continuous testing. The three SMART action items provide measurable improvements for the next sprint. The build pipeline supports the Definition of Done by automating build, test, review and merge activities.