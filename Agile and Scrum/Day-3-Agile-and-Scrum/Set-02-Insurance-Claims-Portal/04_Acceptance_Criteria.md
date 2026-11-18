# Task 4 – Acceptance Criteria

## Project: Insurance Claims Portal

Acceptance criteria define the conditions that must be satisfied for a user story to be considered complete.

The Given/When/Then format is used to describe the expected system behaviour.

## US-01: Secure Login

**User Story:** As a policyholder, I want to log in securely so that I can access my insurance account.

### Scenario 1: Successful Login

- **Given** the policyholder has a registered account with valid login credentials.
- **When** the policyholder enters the correct username and password and selects Login.
- **Then** the system authenticates the user and displays the account dashboard.

### Scenario 2: Invalid Login

- **Given** the policyholder is on the login page.
- **When** the policyholder enters an incorrect password.
- **Then** the system displays an appropriate error message and does not grant access.

## US-02: Select Insurance Policy

**User Story:** As a policyholder, I want to select my insurance policy so that I can register a claim under the correct policy.

### Scenario 1: Select an Eligible Policy

- **Given** the policyholder has an active and eligible insurance policy.
- **When** the policyholder selects that policy.
- **Then** the system displays the selected policy details for claim registration.

### Scenario 2: No Eligible Policy

- **Given** the policyholder has no active eligible insurance policy.
- **When** the policyholder attempts to register a claim.
- **Then** the system informs the policyholder that no eligible policy is available.

## US-03: Enter Incident Details

**User Story:** As a policyholder, I want to enter incident details so that the insurance company understands what happened.

### Scenario 1: Valid Incident Details

- **Given** the policyholder has selected an eligible insurance policy.
- **When** the policyholder enters the incident date, incident type, and description in the required fields.
- **Then** the system accepts the incident details and allows the policyholder to continue.

### Scenario 2: Missing Required Details

- **Given** the policyholder is completing the incident details form.
- **When** the policyholder leaves a mandatory field empty and attempts to continue.
- **Then** the system highlights the missing field and displays a validation message.

## US-04: Submit a Claim

**User Story:** As a policyholder, I want to submit my completed claim details so that the insurance company can begin processing my claim.

### Scenario 1: Successful Claim Submission

- **Given** the policyholder has selected an eligible policy and entered all required and valid claim details.
- **When** the policyholder reviews the information and selects Submit Claim.
- **Then** the system records the claim and displays a successful submission message.

### Scenario 2: Claim Submission Validation Failure

- **Given** the policyholder is on the claim submission page with one or more mandatory fields missing or invalid.
- **When** the policyholder selects Submit Claim.
- **Then** the system prevents submission, highlights the invalid or missing fields, and displays appropriate validation messages.

## US-15: Receive Claim Confirmation

**User Story:** As a policyholder, I want to receive a claim reference number after submission so that I can identify and track my claim.

### Scenario 1: Claim Reference Number Generated

- **Given** the policyholder has successfully submitted a valid claim.
- **When** the system completes claim registration.
- **Then** the system generates and displays a unique claim reference number.

### Scenario 2: Failed Claim Submission

- **Given** the policyholder's claim submission has failed validation.
- **When** the system rejects the submission.
- **Then** the system does not generate a claim reference number.

## Conclusion

The acceptance criteria describe both successful and unsuccessful scenarios for the Claim Registration epic. They provide clear, testable expectations for login, policy selection, incident details, claim submission, and claim confirmation.