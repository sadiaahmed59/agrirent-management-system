# Agrirent Implemented Features
## T-01: FR-Farmer/Admin/Employee-User Registration
Screen Definition: Email & Password, Name, Phone Number field, Signup Button, Third Party SSO
User Story: As a user, I want to create an account so I can access the platform.
Acceptance Criteria: The system validates email, password, re-password, and user type before signup.
The system stores user credentials with inactive status and sends an email verification link.
The system activates the account only after valid email verification and restricts login before verification.
The system allows users to resend verification email and enforces link expiration time.
## T-21: FR-Employee- Schedule Equipment Maintenance 
Screen Definition: Equipment List, Maintenance Date, Status (Scheduled/In Maintenance/Completed), Save Button  User Story: As an employee, I want to schedule maintenance so that equipment remains usable and safe.  Acceptance Criteria:  1. The system should allow employees to assign maintenance dates. If maintenance scheduling fails or not completed, the system does not assign any date and displays an error message: "Maintenance scheduling failed."  2. The system should restrict booking for equipment under maintenance. If maintenance is not active or not scheduled, the system allows the equipment to be booked.  3. The system should display and updates maintenance status when maintenance is scheduled or in progress. If maintenance information is unavailable or not set, the system does not display any maintenance status. The system saves maintenance history after maintenance activities occur. If no maintenance activity is recorded or saving fails, the system does not store any history.  4. The system should display a success message after maintenance is successfully scheduled. If scheduling fails or is incomplete, the system displays an error message: "Maintenance scheduling failed."  Status: Implemented 
