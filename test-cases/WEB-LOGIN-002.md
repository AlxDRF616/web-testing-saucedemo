# WEB-LOGIN-002 – Ambiguous error message and input reset

## Description
Verify system behavior when submitting login form with missing password


## Module
Login


## Preconditions
User is on the "Log In" page


## Test Data
Email: test@example.com  
Password: (empty)


## Steps

1. Navigate to "Log In"
2. Enter a valid email
3. Leave password field empty
4. Click "Sign In"


## Expected Result
- The system should display a clear validation message (e.g., "Password is required")
- The email field should remain populated


## Actual Result
- The system shows a generic error message
- Both fields are cleared


## Status
Failed


## Notes
Poor UX: forcing users to re-enter data increases friction