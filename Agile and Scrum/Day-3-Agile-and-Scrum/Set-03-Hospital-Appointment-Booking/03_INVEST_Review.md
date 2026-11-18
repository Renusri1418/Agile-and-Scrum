# Task 3 – INVEST Review

## Project: Hospital Appointment Booking Application

## 1. What is INVEST?

INVEST is a checklist used to evaluate the quality of user stories.

| Principle | Meaning |
|---|---|
| Independent | Stories should have minimal dependencies on other stories. |
| Negotiable | Stories should allow discussion and refinement. |
| Valuable | Each story should provide value to the user. |
| Estimable | The team should be able to estimate the effort. |
| Small | Stories should be manageable within a sprint. |
| Testable | Stories should have clear conditions for verification. |

## 2. INVEST Evaluation of All User Stories

| Story ID | I | N | V | E | S | T | Result |
|---|---|---|---|---|---|---|---|
| US-01 Search for Doctors | Yes | Yes | Yes | Yes | Yes | Yes | Pass |
| US-02 View Available Slots | Yes | Yes | Yes | Yes | Yes | Yes | Pass |
| US-03 Book an Appointment | No | Yes | Yes | Yes | Yes | No | Needs improvement |
| US-04 View Existing Appointments | Yes | Yes | Yes | Yes | Yes | Yes | Pass |
| US-05 Reschedule Appointment | No | Yes | Yes | Yes | Yes | No | Needs improvement |
| US-06 Cancel Appointment | Yes | Yes | Yes | Yes | Yes | Yes | Pass |
| US-07 Receive Booking Confirmation | No | Yes | Yes | Yes | Yes | No | Needs improvement |
| US-08 Receive Appointment Reminders | Yes | Yes | Yes | Yes | Yes | Yes | Pass |
| US-09 Receive Change Notifications | Yes | Yes | Yes | Yes | Yes | Yes | Pass |
| US-10 Set Doctor Availability | Yes | Yes | Yes | Yes | Yes | Yes | Pass |
| US-11 Update Doctor Availability | Yes | Yes | Yes | Yes | Yes | Yes | Pass |
| US-12 View Doctor Schedule | Yes | Yes | Yes | Yes | Yes | Yes | Pass |

## 3. Stories Identified for Improvement

### US-03 – Book an Appointment

**Original Story:**

As a patient, I want to book an available appointment slot so that I can schedule a consultation with a doctor.

**Issue:**

The story does not clearly define the conditions for a successful booking or how the system handles an appointment slot that has already been taken.

**Rewritten Story:**

As a patient, I want to confirm a selected available appointment slot so that I can successfully schedule a consultation with a doctor.

**Expected Outcome:** The system confirms the appointment only if the selected slot is still available.

### US-05 – Reschedule an Appointment

**Original Story:**

As a patient, I want to select a new available time slot for an existing appointment so that I can change my consultation time.

**Issue:**

The story does not clearly specify that the new slot must be available and that the existing appointment should be updated.

**Rewritten Story:**

As a patient, I want to replace my existing appointment with a newly selected available slot so that I can attend my consultation at a more convenient time.

**Expected Outcome:** The system updates the appointment only after confirming that the new slot is available.

### US-07 – Receive Booking Confirmation

**Original Story:**

As a patient, I want to receive a confirmation notification after booking an appointment so that I know my booking was successful.

**Issue:**

The story depends on successful booking, but does not specify the confirmation information the patient should receive.

**Rewritten Story:**

As a patient, I want to receive a booking confirmation containing the doctor name, appointment date, time, and reference number so that I can verify my appointment details.

**Expected Outcome:** A confirmation notification is sent after a successful appointment booking.

## 4. Why These Stories Were Rewritten

- **Independence:** Each revised story describes a focused outcome without combining unrelated functionality.
- **Testability:** Each story includes a clear expected outcome that can be verified.
- **Value:** The stories directly improve the patient's appointment management experience.
- **Clarity:** The revised stories provide more specific expectations for development and testing.

## 5. Conclusion

The INVEST review evaluated all 12 user stories. Three stories were identified for improvement: US-03, US-05, and US-07.

These stories were rewritten with clearer and more testable outcomes. The updated backlog is now better prepared for acceptance criteria, prioritisation, estimation, and JIRA implementation.