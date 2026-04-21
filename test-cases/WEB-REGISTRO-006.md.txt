# WEB-REGISTRO-006 – Existing email validation

## Description
Verify system behavior when attempting to register with an already existing email


## Module
User Registration


## Preconditions
Email is already registered in the system


## Test Data
Email: existing@example.com  


## Steps

1. Navigate to "Sign Up"
2. Enter an already registered email
3. Fill remaining fields
4. Click "Create"


## Expected Result
The system should reject the registration and display an appropriate error message


## Actual Result
The system displays an error indicating the account already exists


## Status
Passed