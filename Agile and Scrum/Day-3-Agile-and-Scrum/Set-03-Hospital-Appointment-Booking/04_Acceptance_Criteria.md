# Task 4 – Acceptance Criteria

## 1. Introduction

Acceptance criteria define the conditions that must be satisfied for a user story to be considered complete. They are written in the **Given–When–Then** format.

- **Given:** The initial situation or condition.
- **When:** The action performed by the user.
- **Then:** The expected result.

## 2. US-03 – Book an Appointment

**User Story:** As a patient, I want to book an available appointment slot so that I can consult a doctor at a convenient time.

### Scenario 1: Successful appointment booking

- **Given** the patient is logged in and has selected a doctor and an available appointment slot.
- **When** the patient confirms the booking.
- **Then** the system should create the appointment and display a booking confirmation with the appointment details.

### Scenario 2: Slot already taken

- **Given** the patient has selected an appointment slot that was available earlier.
- **When** another patient books that slot before the first patient confirms.
- **Then** the system should inform the patient that the slot is no longer available and ask them to select another slot.

### Scenario 3: Patient does not select a slot

- **Given** the patient has selected a doctor but has not selected an appointment slot.
- **When** the patient tries to confirm the booking.
- **Then** the system should display a message asking the patient to select an available slot.

### Scenario 4: Booking confirmation

- **Given** the appointment has been successfully booked.
- **When** the booking process is completed.
- **Then** the system should display the doctor name, appointment date, time and booking reference number.

## 3. US-06 – Cancel an Appointment

**User Story:** As a patient, I want to cancel an existing appointment so that I can free the slot if I cannot attend.

### Scenario 1: Successful cancellation

- **Given** the patient has an existing appointment.
- **When** the patient selects the appointment and confirms cancellation.
- **Then** the system should cancel the appointment and update its status.

### Scenario 2: Cancellation confirmation

- **Given** the patient has selected an appointment for cancellation.
- **When** the patient confirms the cancellation.
- **Then** the system should display a cancellation confirmation.

### Scenario 3: Patient changes their mind

- **Given** the patient has opened the cancellation option.
- **When** the patient chooses not to proceed with cancellation.
- **Then** the appointment should remain active and unchanged.

### Scenario 4: Appointment not found

- **Given** the patient tries to cancel an appointment that does not exist or is no longer active.
- **When** the patient submits the cancellation request.
- **Then** the system should display an appropriate message and should not create an invalid cancellation.

## 4. Conclusion

These acceptance criteria describe the expected behaviour of the appointment booking and cancellation features. They cover successful actions, invalid actions and situations such as an appointment slot being taken by another patient. They help the development and testing teams understand when each user story is complete.